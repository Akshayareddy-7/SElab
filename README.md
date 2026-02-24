# SElab

https://tinyurl.com/mjfzcbu5
Open Amazon Web Services Console

Go to VPC

Left sidebar → Route Tables

Click Create route table

Select VPC

Give it a name

Click Create

Now click the route table you just created

Go to the Routes tab (this is the key step people miss)

Click Edit routes

Boom 💥 — you’ll see Add route

What to add for a public route table

Destination: 0.0.0.0/0

Target: Internet Gateway (igw-xxxx)

Click Save changes
