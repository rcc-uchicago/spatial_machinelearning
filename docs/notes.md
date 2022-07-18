Instructor in-class setup

Checklist: 
* create reservation 
```bash
scontrol create reservation=workshop users=pnsinha \
  starttime=2022-07-19T13:00:00 duration=5:00:00 \
  partitionname=caslake nodecnt=2

sinteractive -p caslake --reservation=workshop
```

* Download fresh copy of git repository.
* Download fresh copy of data files.
* Test reservation.
* Use Terminal, not iTerm.
* Use Basic Terminal theme (with Consolas font).
