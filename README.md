# pzFalloffAll

MAYA 2022的component tag蠻半套的,先是把舊有的deformer set給預設關閉(可設回來),讓你無法像以前一樣直接套用到新模型上

再來是新的變形器Falloff的功能只能對一個一個物件套用,在變形器下的component tag無法批次套用或是assign....

如果幾百個物件只要共用一個Falloff就很好笑了,所以針對這個問題寫了這個MEL~一次幾個物件也能套用

至於第一個問題舊的DEFROME套給新的模型上其實也有mel可以直接簡單套了,就官方沒弄個介面或指令而已,等忙完在寫
