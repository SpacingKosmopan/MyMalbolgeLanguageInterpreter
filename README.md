# Original Malbolge
 (=<`:9876Z4321UT.-Q+*)M'&%$H"!~}|Bzy?=|{z]KwZY44Eq0/{mlk**
 hKs_dG5[m_BA{?-Y;;Vb'rR5431M}/.zHGwEDCBA@98\6543W10/.R,+O<

# My interpreted
### '<' - return 

### '>' - send

### '@' - take

### '$' - declare

### '&' - wrap (finish this object)

### '/' - use
7+/2 = 9

### '+' - combine
7+2 = 72

### '++' - combine common
"kot"++"ola" = "koto"

### '-' - difference
"kot"-"ola" = ktla

### '--' - common
"kot"--"ola" = "o"

$function @numberOne @numberTwo => {

  /t \t $declare = numberOne /+ numberTwo;
  
  <declare;
  
}

## Short
$f@a@b=><(a/+b);&
