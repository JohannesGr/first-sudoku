# from CLI

usage:
    ## sudoku [-solve|-generate] [-out] [-html] -[verbose]

- solve

          string with 0,1,2,3,4,5,6,7,8,9 or .1,2,3,4,5,6,7,8,9 for the sudoku. Must habe 81 chars.
          default: 000000042000500080000001000000900300200000100400080000090060050010000700000800000

- generate

          integer value between 18 - 80 for the filled cells. Default 20

- out

          where to output the sudoku and solution. Default is std (CLI)

- html

          where to output a html file with the sudoku and solution

- verbose

          how many information for output. 0 ist sudoku and solution, >0 more information. Default = 0


>   `go run . -solve 000000042000500080000001000000900300200000100400080000090060050010000700000800000 -verbose 1`
>
>   `000000042000500080000001000000900300200000100400080000090060050010000700000800000 -> start, -1`
>   `153678942927543681648291537586912374279435168431786295792164853814359726365827419`
>   `iterationen:  595062, Lösungen: 1`
>   `ist Gültig: ja`
>   `duration: 1.327117 seconds`
