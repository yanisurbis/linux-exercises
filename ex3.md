```
1

ls
ls $PWD
ls .

---

2

total 4
-rw-rw-r-- 1 yanis yanis 81 янв 18 20:37 task_4
-rw-rw-r-- 1 yanis yanis  0 янв 18 20:37 testF32
-rw-rw-r-- 1 yanis yanis  0 янв 18 20:37 Testfi13
-rw-rw-r-- 1 yanis yanis  0 янв 18 20:37 testFil32
-rw-rw-r-- 1 yanis yanis  0 янв 18 20:37 Testfile12
-rw-rw-r-- 1 yanis yanis  0 янв 18 20:37 TestFile28
-rw-rw-r-- 1 yanis yanis  0 янв 18 20:37 testfile32
-rw-rw-r-- 1 yanis yanis  0 янв 18 20:37 testFile32
-rw-rw-r-- 1 yanis yanis  0 янв 18 20:37 testFile53

ls -l Test*1[23] test[fF]?*32

---

3

cd ../../../../../lib/test

---

4

head -n -4 task_4 | tail -n +15

---

5

C1 $ touch log

C2 $ tail -f log  | grep -iw "alert"
alert - we have a situation
Alert - like serious situation

C1 $ cat >> log <<EOF
> alert - we have a situation
> notice - or not
> Alert - like serious situation
> notalert - I'm just passing here
> warning - not sure if I should be alerting right now
> bash: warning: here-document at line 94 delimited by end-of-file (wanted `EOF')
```