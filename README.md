# AdadKhodMoghaleb.php
https://quera.org/problemset/617?tab=description
<?php
$n = (int)readline("Enter a number: ");
$m = (preg_split('//u', $n, null, PREG_SPLIT_NO_EMPTY));
$w = array_reverse($m);
if($m == $w){
	echo "YES";
}else{
	echo "NO";
}
