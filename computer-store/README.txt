We are starting a computer store. You have been engaged to build the checkout system.
We will start with the following products in our catalogue:
| SKU | Name | Price |
| -------- |:--------------------:| --------:|
| ipd | Super iPad | $549.99 |
| mbp | MacBook Pro | $1399.99 |
| atv | Apple TV | $109.50 |
| vga | VGA adapter | $30.00 |

As we're launching our new computer store, we would like to have a few opening day specials.
● We're going to have a 3 for 2 deal on Apple TVs. For example, if you buy 3 units of
Apple TVs, you will only pay for the price of 2 units
● The brand new Super iPad will have a bulk discount applied, where the price will drop to
$499.99 each, if someone buys more than 4 units
● We will bundle in a VGA adapter free of charge with every MacBook Pro sold

Our checkout system can scan items in any order.

Your task is to implement a checkout system that fulfils the requirements described above.
Example scenarios:
SKUs Scanned: atv, atv, atv, vga
Total expected: $249.00
SKUs Scanned: atv, ipd, ipd, atv, ipd, ipd, ipd
Total expected: $2718.95
SKUs Scanned: mbp, vga, ipd
Total expected: $1949.98

Steps to test the solution I have provided:
- Type SKUs and press enter. For example, type atv and press <enter>. Continue to type the SKUs one by one and press <enter>.
- Once done, click Get Total button. 
