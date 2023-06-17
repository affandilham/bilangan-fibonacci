package main

import "fmt"

func main() {

     var n int
     term1 := 0
     term2 := 1
     nextTerm := 0
     
     fmt.Print("\n\n")
     fmt.Print("\tBilangan Fibonacci Golang")
     fmt.Print("\n\n")
     fmt.Print("\tMasukkan bilangan bulat positif: ")
     fmt.Scan(&n)
     fmt.Print("\n")
     fmt.Print("\tUrutan bilangan fibonacci adalah:")
     fmt.Print("\n\n")
     fmt.Print("\t")
     for i := 1; i <= n; i++ {
         if i == 1 {
             fmt.Print(" ", term1)
             continue
         }
         if i == 2 {
             fmt.Print(" ", term2)
             continue
         }
         nextTerm = (term1 + term2)
         term1 = term2
         term2 = nextTerm
         fmt.Print(" ", nextTerm)
     }    
     fmt.Print("\n\n")
     fmt.Print("\tAkhir Program")
     fmt.Print("\n\n")
}
