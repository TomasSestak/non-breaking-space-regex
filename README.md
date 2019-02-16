# non-breaking-space-regex
Regular expression for Find and replace in Visual Studio Code for Czech language to quick add non-breaking spaces

## Find<br>
<code>([ |>|0-9])([k,s,v,z,o,u,i,a] [k,s,v,z,o,u,i,a]|[k,s,v,z,o,u,i,a]|\+[0-9]+|[0-9]+|[0-9]+\.)([ ])</code>

## Replace<br>
<code>$1$2\&nbsp;</code>

### Check more because it's impossible to have one regex for all cases
https://cs.wikipedia.org/wiki/Nezlomiteln%C3%A1_mezera
