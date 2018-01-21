# Linux

```shell
# 从nginx log 中排序并输出IP 
cut -f1 -d ' ' example.com.access.log | sort | uniq -c | sort -g -r
```

