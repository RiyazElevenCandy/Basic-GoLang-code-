package main

import (
	"fmt"
	"reflect"
)

func main() {

	var a int = 10 //Declaration with initialization
	var b string = "eleven"
	fmt.Println(a)
	fmt.Println(b)

	
	var i = 11 //Declaration with type inference
	var j = "candy"
	fmt.Println(reflect.TypeOf(i))
	fmt.Println(reflect.TypeOf(j))

	
	
	var fname, lname string = "riyaz", "pasha" //Declaration of multiple variables
	m, n, o := 1, 2, 3
	item, price := "mobile", 2000 //:= Short Variable Declaration
	fmt.Println(fname + lname)
	fmt.Println(m + n + o)
	fmt.Println(item, "-->", price)



	const ( //Multilple Constants Declaration Block
		PRODUCT  = "Mobile"
		QUANTITY = 50
		PRICE    = 50.50
		STOCK    = true
	)
	fmt.Println(PRICE)
	fmt.Println(PRODUCT)
	fmt.Println(STOCK)

	
	
	x := 100 //if else if else

	if x == 50 {
		fmt.Println("Germany")
	} else if x == 100 {
		fmt.Println("Japan")
	} else {
		fmt.Println("Canada")
	}

	
	
	var emp [5]int // slice of type int
	emp[0] = 1     //0 is index ,value is 1
	emp[1] = 11
	emp[2] = 33
	emp[3] = 55
	fmt.Println(emp)
	
}
