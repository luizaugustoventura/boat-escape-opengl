# OpenGL: Jogo Boat Escape

  Projeto desenvolvido na disciplina de Computação Gráfica(7º Período) do Curso de Ciência da Computação, onde foi solicitado pela professora Jaqueline o desenvolvimento de um projeto OpenGL 3D que utilize recursos de iluminação.

  Para que este projeto funcione, é necessário que se importe duas bibliotecas fundamentais, a GLUT(Graphics Library Utilitty Toolkit) e a OpenGL, obviamente. Para tal, utilizo o Tao Framework. Após instalá-lo, você pode adicionar as bibliotecas mencionadas nas referências do projeto, e, logo após, importá-las normalmente no seu código. Para isso, recomendo o seguinte tutorial: https://codeyarns.com/2013/06/18/how-to-get-started-with-tao-framework-using-c/ 

  É necessário compilar o projeto pelo menos uma vez, para que o Visual Studio possa criar o caminho "bin/Debug" dentro do projeto. Nesta pasta ficará o aplicativo final compilado para linguagem de máquina. 

  Certo, se você realizou o passo descrito acima, notará que uma excessão foi gerada. Pois bem, isso aconteceu porque a biblioteca GLUT do Tao Framework tem como dependência a DLL "freglut.dll" que acompanha o projeto. Para resolver este problema, você terá que mover esta DLL para o caminho "bin/Debug" do projeto. Por isso lhe pedi que compilasse o projeto primeiramente. 
  
##### Outros desenvolvedores: Willian Pereira Mariano  


#### Capturas de tela:

![Captura do jogo](screenshots/captura_game.png)

![Captura da pontuação](screenshots/captura_score.png)


