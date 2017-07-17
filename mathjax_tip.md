# Mathjax require a prefix `\` to recoginize _. ex)`p\_{a}`, not `p_{a}`

texでは関数(?)の識別に接頭辞`\`が使われる。

しかし一部はそれが省略可能で、たとえば下付き文字は_のみで表現可能だが、下付き文字にさらに下付き文字を付ける場合などは、識別子を明示しなければならない。


$$ e^{-\frac{1}{N}\sum\_{i=1}^{N} \ln p_{\text{target}_i}} = e^{\text{loss}} $$




