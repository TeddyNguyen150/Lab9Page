1)
Hello,
I was working on the dot product file and was editing the length of the vectors when I got 0.0 when it should been NaN. Thank you.
![image](https://github.com/TeddyNguyen150/Lab9Page/assets/156158048/6024049f-a9b3-4984-a1f6-4801bf227580)
![image](https://github.com/TeddyNguyen150/Lab9Page/assets/156158048/6e4f085e-9d91-45db-ae00-40c0ee1c7e08)

2)
The problem might have to do with the magnitude function because, the main reason why your value is NaN in 3 dimensions is because
v2 is a 0-vector in 3 dimensions, whose magnitude is NaN because you cannot divide a number by 0. If you wanted to just measure in
3 dimensions you can modify your magnitude function to only use the dimensions of the first vector instead of the second one.

3)
Thank you! The problem was the magnitude function. Since v1 was in a lower dimension than v2, I had to specify that I wanted to get
the dot product in R3.
![image](https://github.com/TeddyNguyen150/Lab9Page/assets/156158048/e7240d9a-38c3-4710-aa72-892e91e37efe)

4)
BEFORE:
![image](https://github.com/TeddyNguyen150/Lab9Page/assets/156158048/a344e801-6c40-4068-b829-7c0cf1a49e03)
![image](https://github.com/TeddyNguyen150/Lab9Page/assets/156158048/5d0e9dc1-1504-41a9-a4c4-05f5bf34c2ea)
![image](https://github.com/TeddyNguyen150/Lab9Page/assets/156158048/9fddf64e-5b7d-47c3-9194-14e6ecb91966)

AFTER:
![image](https://github.com/TeddyNguyen150/Lab9Page/assets/156158048/363f18cf-3ac3-4df9-b552-d9167f22c119)
![image](https://github.com/TeddyNguyen150/Lab9Page/assets/156158048/cde3871f-6123-4e35-b04b-e7e5e0d1247e)
![image](https://github.com/TeddyNguyen150/Lab9Page/assets/156158048/21165e55-9222-4486-b1a5-caf32eac4da9)

REFLECTION:
I was surprised about how github worked. I was meaning to look into it, but I never did since I mainly focused on my own projects,
but seeing how it works and how technical it really is kind of overwhelmed me for a bit. I will definitely try to get better at it
though.
I was also surprised we used vim for java and bash because I used vim in ECE 15 which is mainly C and didn't expect it to appear in
files in general.
