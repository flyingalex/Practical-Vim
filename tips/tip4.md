###4.Act, Repear, Reverse

Edition means change and move all the time.If we can just do them one time,and then repeat them,it will be very effective.But sometimes we also will make a mistake when we repeat them, so undo a operation is very important.Vim provide some operations for this.

| Purpose | Operation | Repeatation | Reverse |
|-----------------------------------|-----------------------|---|---|
|Make a change 						| {edit} 				| . | u |
|Scan line for next character		| f{char} / t{char} 	| ;	| , |
|Scan line for previous character	| F{char} / T{char} 	| ;	| , |
|Scan document for next match		| /pattern <CR> 		| n | N | 
|Scan document for previous match	| ?pattern <CR> 		| n | N |
|Perform substitution				| :s/target/replacement | & | u |
|Execute a sequence of changes 		| qx{changes}q 			| @x| u |