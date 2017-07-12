# treinamento-swift

1. [Exercícios](https://github.com/CWISoftware/treinamento-ios)
2. [Alamofire - HTTP lib](https://github.com/Alamofire/Alamofire)
3. [Wiremock](http://wiremock.org/docs/api/)

```
pod init
pod install

adicionar no info.plist
<key>NSAppTransportSecurity</key>  
<dict>  
   <key>NSAllowsArbitraryLoads</key><true/>  
</dict>
```

1. NavigationController : colocar o primeiro vinculo como "RootViewController" segurando a tecla control.
2. StackView align distributtion para fazer o autoresize.
3. Não usar TableView dentro de ScrollView.
4. Command + Click: navega para o método.
5. Command + = : atualiza as cosntraints.
6. Acessos a Photo Library, Câmera, etc precisam de permissão do usuário: Adicionar no info.plist as TAGs: Privacy - Camera Usage Description e Privacy - Photo Library Usage Description
7. QuickTime: conecta no iPhone para rodar o APP no dispositivo, testar camera, etc...
