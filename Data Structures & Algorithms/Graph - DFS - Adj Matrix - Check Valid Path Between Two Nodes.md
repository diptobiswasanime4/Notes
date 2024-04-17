Created: April-16-2024

Leetcode 1971

```cpp

    bool validPath(int n, vector<vector<int>>& edges, int source, int destination) {

        if (source == destination) {

            return true;

        }

        vector<vector<int>> matrix(n, vector<int> (n, 0));

        vector<int> vis_arr(n, 0);

        int size = edges.size();

        for (int i = 0; i < size; i++) {

            int u = edges[i][0], v = edges[i][1];

            matrix[u][v] = 1;

            matrix[v][u] = 1;

        }

        dfs(matrix, source, destination, vis_arr, n);

        if (vis_arr[destination] == 1) {

            return true;

        } else {

            return false;

        }

    }

    void dfs(vector<vector<int>>& matrix, int source, int destination, vector<int> &vis_arr, int n) {

        for (int i = 0; i< n; i++) {

            if (matrix[source][i] == 1) {

                if (vis_arr[i] != 1) {

                vis_arr[i] = 1;

                dfs(matrix, i, destination, vis_arr, n);

                }

            }

        }

    }
```


# Related Notes

1. [[Data Structures & Algorithms]]
2. [[Data Structure]]
3. [[Algorithm]]
4. [[Graph]]
# References

1. 