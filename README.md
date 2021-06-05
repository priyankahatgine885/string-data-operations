input:
22, Anand, Engineering, 1600000
23, Swati Patil, Testing, 800000
27, Vijay Chawda, Engineering, 800000
29, Basant Mahapatra, Engineering, 600000
32, Ajay Patel, Testing, 350000
34, Swaraj Birla, Testing, 350000


#1.output:
Key: 22, Value: {22, Rajan Anand, Engineering, 1600000}
Key: 23, Value: {23, Swati Patil, Testing, 800000}
Key: 27, Value: {Vijay Chawda, Engineering, 800000}
Key: 29, Value: {29 Basant Mahapatra, Engineering, 600000}
Key: 32, Value: {32, Ajay Patel, Testing, 350000}
Key: 34, Value: {34, Swaraj Birla, Testing, 350000}

#2.output:
Key: Engineering, Value: [
{ 22, Rajan Anand, Engineering, 1600000 },
{ 27, Vijay Chawda, Engineering, 800000 },
{ 29, Basant Mahapatra, Engineering, 600000 }
]
Key: Testing, Value:     [
{ 23, Swati Patil, Testing, 800000 },
{ Ajay Patel, Testing, 350000 },
{ 34, Swaraj Birla, Testing, 350000 }
]