```
1

gunzip -c log.gz | less

---

2

zgrep -w rebrainme log.gz

---

3

zip logs.zip rebrainme
unzip -o logs.zip

---

4

tar cf log1.tar log1
tar czf log2.tar.gz log2
tar cfJ log3.tar.xz log3

---

5

так, к сожалению, не сработало, в мане тоже ничего не нашел, как и в сети
есть -T, но, если я правильно понимаю, это совсем не то

cat log.pipeline | gzip -c | tar cf log.pipeline.tar.gz -

```