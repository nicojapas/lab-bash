Bash Lab

1)
echo "Hello World"

2)
mkdir new_dir

3)
rm -rf new_dir

4)
cp lorem/sed.txt lorem-copy.txt

5)
cp lorem/at.txt lorem-copy/at.txt; cp lorem/at.txte lorem-copy/at.txte

6)
cd lorem
cat sed.txt

7)
cat at.txt; cat lorem.txt

8)
head -n 3 sed.txt

9)
tail -n 3 sed.txt

10)
cd ..
cd lorem-copy
echo >> "Homo homini lupus" sed.txt

11)
tail -n 3 sed.txt

12)
sed -i "s/et/ET/g" at.txt

13)
whoami

14)
pwd

15)
ls *.txt

16)
cat sed.txt | wc -l

17)
ls lorem* | wc -l

20)
read var1

21)
echo $var1

22)
mkdir $var1

23)
rm -rf $var1