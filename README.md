# datastruct
userful simple datastruct
##list.h
usage as 
```
typedef struct test_list
{
    struct list list
    int data
}_Test;

void main()
{
   _Test *pstHead = (_Test*)malloc(sizeof(_Test));
   list_init(&pstHead.list);
   _Test *pstNewNode = (_Test*)malloc(sizeof(_Test));
   list_append(&stHead.list, &pstNewNode->list);
   return;
}

then， pstHead and pstNewNode was linked by list, and user can use list to find the data.
```
