/*
 * 给定一个字符串， 找出第一个不重复的字符。返回该字符的坐标index, 或者-1
*/

int NoDuplicate(const string& str) {
    int k = str.size();
    for (int i = 0; i < k - 1; ++i) {
        char c = str[i];
        bool b = false;
        for (int j = 0; j < k - 1; ++j) {
            if (j == i) continue;
            if (c == str[j]) {
                b = true;
                break;
            }
        }
        if (!b) {
            return i;
        }
    }
    return -1;
}
