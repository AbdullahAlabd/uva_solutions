#include <bits/stdc++.h>
using namespace std;
typedef long long ll;

const int MAXN = 1e6+6;

int main() {
    char A[][15] = {
    "`1234567890-=",
    "QWERTYUIOP[]\\",
    "ASDFGHJKL;'",
    "ZXCVBNM,./"
    "  "
    };
    char toL[256] = {};
    for(int i = 0; i < 5; i++) {
        int n = strlen(A[i]);
        for(int j = 1; j < n; j++) {
            toL[(int)A[i][j]] = A[i][j-1];
        }
    }
    string s;
    while(getline(cin, s)) {
        int i = 0;
        while(s[i]) {
            printf("%c", toL[(int)s[i++]]);
        }
        puts("");
    }
}
