**Bài 1:**

git clone https://github.com/ntnanh25174600029-ai/25174600029\_Ngo\_Thi\_Ngoc\_Anh\_bai\_tap.git

cd 25174600029\_Ngo\_Thi\_Ngoc\_Anh\_bai\_tap

**Bài 2:**

\# Mở file README.md và chỉnh sửa nội dung:

"""

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer efficitur, eros at

lacinia suscipit, magna turpis aliquam est, sit amet aliquam quam libero id mi. Ut vel

placerat risus. Sed tempor in ex vitae sodales. Donec et tempor orci. In pharetra

viverra sagittis. Vestibulum risus ante, molestie ac eros efficitur, bibendum tincidunt

turpis. In sit amet tortor gravida, ultricies ante vitae, varius tortor. Aliquam finibus

porta nulla sed gravida. Aliquam ultricies dapibus ante eget molestie. In hac habitasse

platea dictumst. Aliquam aliquam enim at massa pharetra, et vestibulum sapien

consequat. Donec accumsan quis metus at pellentesque. Morbi quis felis placerat,

interdum justo a, aliquam risus.

"""

git add .

git commit -m "Cập nhật nội dung README.md"

git push origin main

**Bài 3:**

git checkout -b branch\_1

echo "Lorem ipsum dolor sit amet, consectetur adipiscing elit." > text\_branch\_1.txt

git add .

git commit -m "Thêm text\_branch\_1.txt"

git push origin branch\_1



git checkout main

git checkout -b branch\_2

echo "Praesent ullamcorper orci eu erat placerat sodales." > text\_branch\_2.txt

git add .

git commit -m "Thêm text\_branch\_2.txt"

git push origin branch\_2



git checkout main

git checkout -b branch\_3

echo "Integer sit amet nisi aliquam, tempor libero quis, cursus erat." > text\_branch\_3.txt

git add .

git commit -m "Thêm text\_branch\_3.txt"

git push origin branch\_3



git checkout main

git checkout -b branch\_4

echo "Cras ac mi nec nisi porta ultrices sed non ante." > text\_branch\_4.txt

git add .

git commit -m "Thêm text\_branch\_4.txt"

git push origin branch\_4

**Bài 4:**

git branch --delete branch\_4

git branch --delete branch\_4

**Bài 5:**

git pull

**Bài 6:**

mkdir main\_folder

echo "Nội dung file 1" > main\_folder/main\_txt\_1.txt

echo "Nội dung file 2" > main\_folder/main\_txt\_2.txt

echo "Nội dung file 3" > main\_folder/main\_txt\_3.txt

git add .

git commit -m "Thêm thư mục main\_folder và 3 file bên trong"

git push origin main

git pull

**Bài 7:**

git checkout branch\_1

git checkout -b branch\_5

echo "Etiam malesuada felis nulla, ac porta dui sollicitudin eget. Mauris hendrerit non metus eget pellentesque. Etiam ornare ante at pretium hendrerit. Proin molestie

accumsan sapien, ac finibus libero lobortis quis. Praesent ac commodo eros. Nullam

malesuada vel dui nec feugiat. Cras justo ipsum, scelerisque et elit vitae, porttitor

tristique turpis. Nam ut hendrerit est. Nulla sed tincidunt nibh. Class aptent taciti

sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Quisque vitae

egestas lacus. Phasellus turpis ante, euismod quis pellentesque et, pharetra id ligula.

Vestibulum mattis sem ac ligula auctor viverra. Phasellus dignissim mollis leo, vitae

tristique enim." > text\_branch\_1.txt



git add .

git commit -m "Cập nhật nội dung text\_branch\_1.txt trong branch\_5"

git push origin branch\_5

git branch -d branch\_5

**Bài 8:**

git status

git checkout main

git merge branch\_1 --no-ff -m "Merge branch\_1 into main"

git merge branch\_2 --no-ff -m "Merge branch\_2 into main"

git merge branch\_3 --no-ff -m "Merge branch\_3 into main"

git merge branch\_4 --no-ff -m "Merge branch\_4 into main"

ls

git push origin main  

git branch

cat text\_branch\_1.txt

cat text\_branch\_2.txt

cat text\_branch\_3.txt

cat text\_branch\_4.txt

**Bài 9:**

git branch -d branch\_2

git branch -d branch\_3

git branch -d branch\_4



git push origin --delete branch\_2

git push origin --delete branch\_3

git push origin --delete branch\_4

git checkout branch\_1

git pull origin main

git push origin branch\_1



