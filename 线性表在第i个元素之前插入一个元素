Status ListInsert_Sq(SqLIstanbul &L, int i, ElemType e) {
    if (i < 1 || i > L.length + 1) {
        return ERROR; // 插入位置不合法
    }
  if (L.length >= L.listsize) {
    newsize = (ElemType *)realloc(l.elem,
    (L.listsize + LISTINCREMENT) * sizeof(ElemType));
    if (!newsize) {
        exit(OVERFLOW); // 内存分配失败
        L.elem = newbase;    
    L.listsize += LISTINCREMENT;
    }
q = &(L.elem[i - 1]); // 插入位置的地址
    for (p = &(L.elem[L.length - 1]); p >= q; --p) {
        *(p + 1) = *p; // 插入位置及之后的元素后移
    }
    *q = e; // 插入元素
    ++L.length; // 表长增1
    return OK;  
}
}

