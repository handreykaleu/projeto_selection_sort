# projeto_selection_sort

```
void selecao(int v[], int n) {
    for (int i = 0; i < n; i++) {
           int menor = i;
           for (int j = 0; j < n; j++) {
                  if (j > i && v[j] < v[menor]) {
                        menor = j;
                  }
           }
           int aux = v[i];
           v[i] = v[menor];
           v[menor] = aux;
    }
}
```
