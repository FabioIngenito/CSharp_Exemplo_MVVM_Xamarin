<h1 align="left">EXEMPLO MVVM EM C# XAMARIN</h1>

| :placard: Vitrine.Dev |  |
| -------------  | --- |
| :sparkles: Nome        | **CSharp_Exemplo_MVVM_Xamarin**
| :label: Tecnologias | C# MVVM Xamarin

![exemplo_mvvm20210616282J20M562](https://user-images.githubusercontent.com/24603753/205398222-f430f1aa-997d-4cbb-84e2-f3637dd5c7d5.png#vitrinedev)

<h2 align="left">Detalhes do projeto</h2>

# 
Exemplo baseado em um vídeo do J. C. Macoratti mas com algumas modificações minhas. C# VS2019.
Example based on a video of J.C. Macoratti but with some my modifications. C# VS2019.

BASEADO NO EXEMPLO:

 Xamarin Forms - Apresentando o MVVM
 3 de dez. de 2016
 Jose Carlos Macoratti
 https://youtu.be/DN6Bs8FuTfA

O que é o MVVM?
 - O MVVM é um padrão de arquitetura para implementar interfaces do usuário que ajuda você a separar a lógica de negócios e a lógica de apresentação do seu aplicativo da sua Interface de Usuário (UI).
 
É composto por três componentes:
 
1. Model
 - Representa os objetos de negócio que encapsula os dados e o comportamento do domínio da aplicação (classes C#);
 
2. View 
 - É o que o usário visualiza e interage; No Xamarin Forms é a página (Page);

3. ViewModel
 - É um Model projetado especificamente para a View. Ela contém propriedades que representam o estado da View e métodos que que implementam a lógica por trás da View (Classes #).


LEMBRE-SE SEMPRE!
 - ALTA COESÃO E BAIXO ACOMPLAMENTO;
 - SEPARE a "lógica de negócios" da "lógica de apresentação";
 - Melhore a reutilização de código;

... Mas se o seu projeto for muito simples e não ter TDD (Test Driven Development), não é tão interessante usar MVVM.
... Se o código ficar em seu ".cs" o acoplamento será muito alto!!!


* Leia também:
 
Xamarin Forms - MVVM, DataBinding e a interface ICommand - II
http://www.macoratti.net/16/11/xamforms_icmd2.htm

O padrão Model-View-ViewModel
07/08/2017
22 minutos para o fim da leitura
https://docs.microsoft.com/pt-br/xamarin/xamarin-forms/enterprise-application-patterns/mvvm
