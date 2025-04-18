# FastIO
My Fastio Implementation.

## How To Use?

```c
ll a;
read_int(a);
```

reading integer value a.

```c
string s;
s=read_str();
```

reading string value a.

```c
string s;
read_line(s);
```

read line.</br> 
better than read_str.

```
ll a;
read_int_safe(a);
```

reading integer value a. </br>
read_int is unsafe.

```c
double x;
read_double(x);
```

reading double value x.

```c
flush();
```

flushing buffer.

```c

write_int(x);
write_str("Hello!");
write_double(dx,9);
```

write_int is writing integer value x.</br>
and write_str is writing string value, </br>
write_double is writing dx. default precision is 9, </br>
you can setting custom precision!
