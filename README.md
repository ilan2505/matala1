# Ex2
# Authors : 
* Souffir Ilan Meyer
* Boritsky Jonatan

## Subject of Ex2 :
In this task you should train data structures and threading skills.
The background for this task is this:
You have a endless datastream that should be processed fast. Say a security camera data, where an 
intrusion should be detected.
In our assinment we will use a random number generator (provided) that simulates the endless stream, 
and your task is to count the number of prime numbers in this stream.
The idea is to parallelize the process, so all the cpu core are utilized.
You may improve the isPrime function too, if nessesary.
Note that you allowed to use only 2MB of ram space. <br>
You should do a least 4 times better without improving the isPrime function (90% mark) <br>
You should do a least 10 times better with improving the isPrime function (10% mark)


## How to run the project ?
First of all, you need to write this command when you open the terminal of the folder : 
```
make all
```
and then for the old solution :
```
./generator <seed> <num_of_numbers> | ./newPrimeCounter <seed> <num>
```
and for our solution :
```
./generator <seed> <num_of_numbers> | ./newPrimeCounter <seed> <num>
```
Where :
<num> is or 1 (without improving the isPrime function) or 2 (with improving the isPrime function).

## time for the old solution:
<p align="center">
  <img align="center" width=60% src = "https://github.com/ilan2505/matala1/assets/55143087/9acb1c14-9c78-4806-a478-67be96ee5636"/>
</p>

## Results on 10 000 000:
<p align="center">
  <img align="center" width=60% src = "https://github.com/ilan2505/matala1/assets/55143087/98e90797-5d7c-43ff-995f-fb4fffeeb215"/>
</p>

## Check if < 2MB:
<p align="center">
  <img align="center" width=60% src = "https://github.com/ilan2505/matala1/assets/55143087/9e903ee1-91da-44be-a33e-9291556731ef"/>
</p>









