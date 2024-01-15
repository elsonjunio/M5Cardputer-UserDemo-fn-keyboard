Tecla fn do M5Cardputer

No código de demonstração do M5Cardputer ao utiliza-lo como teclado, percebi a tecla `fn` não estava funcionando, ela deveria ativar as teclas de navegação, delete e esc. Criei este patch para adicionar esta funcionalidade.


```
git clone https://github.com/m5stack/M5Cardputer-UserDemo.git
cd M5Cardputer-UserDemo-fn-keyboard
git checkout 7f98f9d2e13e474521f33618be134e2d56458659
git apply ../fn-keyboard.patch 
```

