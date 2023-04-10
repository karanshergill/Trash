### Generate Numbers in Sequence
```CSS
▶ for i in $(seq -f "%02g" 1 100); do echo $i >> numbers.txt; done
```

### Generate Dates (2030-02-28) and Download Files
```CSS
▶ for day in $(seq -f "%02g" 1 100); do for month in $(seq -f "%02g" 1 100); do wget -nv https://pwnstuff.com/downloads/2020-$month-$day-document.pdf 2>/dev/null; done;  done
```

