Created: April-16-2024

Leetcode 1971

```cpp

    bool validPath(int n, vector<vector<int>>& edges, int source, int destination) {

        vector<vector<int>> matrix(n, vector<int> (n, 0));

        for (auto edge: edges) {

            int u = edge[0];

            int v = edge[1];

            matrix[u][v] = 1;

            matrix[v][u] = 1;

        }

  

        queue<int> q;

        q.push(source);

  

        vector<int> vis_arr(n, 0);

        vis_arr[source] = true;

  

        while(!q.empty()) {

            int cur = q.front();

             if (cur == destination) {

                return true;

             }

             for (int i = 0; i < n; i++) {

                if (matrix[cur][i] == 1 && vis_arr[i] == 0) {

                    vis_arr[i] = 1;

                    q.push(i);

                }

             }

             q.pop();

        }

        return false;

    }
```
# Related Notes

1. [[Data Structures & Algorithms]]
2. [[Data Structure]]
3. [[Algorithm]]
4. [[Graph]]
# References

1. 