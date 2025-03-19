Experiment 8 
Write shell scripts to print system information. 
Implimentation:
echo "System Information:"
echo $(lscpu)
![systeminfoAnswer](https://github.com/user-attachments/assets/54a3ff4e-978e-41e8-8321-3d556df7c0fb)


Write shell script to perform basic mathematical 
calculation. 
Implimention:
echo "Enter the 1st number"
read num1
echo "Enter the 2nd number"
read num2
echo Addition: $((num1 + num2))
echo Substractiuon: $((num1 - num2))
echo Multiply: $((num1 * num2))
if [ $num2 -ne 0 ];
then 
echo Divide: $((num1/num2))
else
echo Undefined
fi
![calculatorAnswer](https://github.com/user-attachments/assets/087568a9-8265-47a3-a9f1-0ec9bae729e4)

