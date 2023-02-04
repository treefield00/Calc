# Calc
Pythonで四則演算と剰余と冪乗の混在する式の計算を逆ポーランド記法で実装  
使える演算子 　
+：加算、-：減算、*：乗算、/：除算、%：剰余、^：冪乗、()：括弧  
  
計算に使用する関数  
calc  
```
# calcの使い方
exp = '1.0+(-20.0*(0.50+4)/2*(3-1.8))-1'
calc(exp)
# -54
```
  
calc関数内で使用する関数  
get_token_list  
check_parenthesis  
operate  
print_Token
  
トークン格納用クラス  
Token  


