- ## Problema 1
  type:: problem
  unit:: 0
	- El movimiento de una pelota viene dado por el siguiente vector de posición (SI):
		- $$\vec r(t)=4t\vec i+(t^2+2t)\vec j$$
		- Calcular:
		- a.- La posición en el instante t=5 s.
		  b.- El vector desplazamiento entre t=3 s y t=5 s.
		  c.- La ecuación de la trayectoria de la pelota.
		  d.- La velocidad y la aceleración en el instante t=2 s.
	- ## Solución
		- $$
		  \begin{gathered}
		  \vec{r}(t)=4 t \vec{i}+\left(t^2+2 t\right) \vec{j} \\
		  \vec{v}(t)=\frac{d \vec{r}(t)}{d t}=4 \vec{c}+(2 t+2) \vec{j} \\
		  \vec{a}(t)=\frac{d v(t)}{d t}=2 \vec{j}
		  \end{gathered}
		  $$
		- ### Apartado a)
			- $$
			  \vec{r}(5)=(4 \cdot 5) i+\left(5^2+(2 \cdot 5)\right) \vec{j}=20 \vec{i}+35 \vec{j}
			  $$
			- $$
			  \boxed {\vec r(5)=2 \vec{i}+35 \vec{j}}
			  $$
		- ### Apartado b)
		- $$
		  \vec{r}(3)=(4 \cdot 3) \vec{i}+\left(3^2+(2 \cdot 3) \vec{j}=12 \vec{i}+15 \vec{j}\right.
		  $$
		- $$
		  \vec{d}_{(3,5)}=\vec{r}(5)-\vec{r}(3)=20 \vec{l}+35 j-12 \vec{i}-15 \vec{j}=8 \vec{i}-20 \vec{j}
		  $$
		- $$\boxed{\vec{d}_{(3,5)}}=8 \vec{i}-20 \vec{j}$$
		- ### Apartado c)
			- $$
			  \left.\begin{array}{l}
			  x=4 t \\
			  y=t^2+2 t
			  \end{array}\right\} t=\frac{x}{4}
			  $$
			- $$
			  y=\frac{x^2}{16}+\frac{x}{2} \Rightarrow \boxed{y=\frac{1}{8} x^2+x}
			  $$
		- ### Apartado d)
			- $$
			  \begin{aligned}
			  & \vec{v}(2)=4 \vec{i}+6 \vec{j} \\
			  & \vec{a}(2)=2 \vec{j}
			  \end{aligned}
			  $$
- ## Problema 2
  type:: problem
  unit:: 0
	- El vector de posición de un cuerpo viene dado por (SI): $\vec r(t)=(t^3-2)\vec i +(2t^2-1)\vec j$
		- Calcula las componentes intrínsecas de la aceleración para $t = 2 s$.
	- ## Solución
		- Partimos del vector posición:
			- $$
			  r(t)=\left(t^3-2\right) \vec{i}+\left(2 t^2-1\right) \vec{j}
			  $$
		- Derivamos y obtenemos el vector velocidad:
		- $$
		  \vec{v}(t)=\frac{d \vec{r}(t)}{d t}=3 t^2 \vec{i}+4 t \vec{j}
		  $$
		- Hallamos el módulo del vector velocidad:
		- $$
		  |\vec v(t)|=\sqrt{\left(3 t^2\right)^2+(4 t)^2}=\sqrt{9 t^4+16 t^2}
		  $$
		- Derivamos el vector aceleracion y obtenemos el vector aceleracion total
		- $$
		  \vec{a}(t)=\frac{d \vec{v}(t)}{d t}=6 t \vec{i}+4 \vec{j}
		  $$
		- Hallamos el módulo del vector aceleración total
		- $$|\vec{a}(t)|= a(t)=\sqrt{6 t^2+4^2}$$
		- Hallamos la aceleracion tangencial derivando el módulo de la velocidad:
		- $$
		  a_t(t)=\frac{d v(t)}{d(t)}=\frac{36 t^3+32 t}{2 \sqrt{9 t^4+16 t^2}}
		  $$
		- Por el teorema de Pitagoras:
		- $$
		  \begin{aligned}
		  & a(t)^2=a_t(t)^2+a_n(t)^2 \\
		  & a_n(t)^2=a(t)^2-a_t(t)^2 \\
		  & a_n(t)=\sqrt{a(t)^2-a_t(t)^2}
		  \end{aligned}
		  $$
		- Para $t=2$
			- $$
			  a_t(2)=\frac{36 \cdot 2^3+32 \cdot 2}{2 \sqrt{9 \cdot 2^4+16 \cdot 2^2}}=12.20 \mathrm{~m} / \mathrm{s}^2
			  $$
		-
			- $$
			  \vec{a}(2)=12 \vec{i}+4 \vec{j}
			  $$
			- $$
			  |\vec a(2)|=a(2)=\sqrt{12^2+4^2}=12.65 \mathrm{~m} / \mathrm{s}^2
			  $$
				- $$
				  a_n(2)=\sqrt{a(2)^2-a_t^2(2)^2}=\sqrt{12.65-12.20}=3.34 \mathrm{~m} / \mathrm{s}^2
				  $$
				- $$\boxed {a_t(2)=12.20 \mathrm{~m} / \mathrm{s}^2}$$
				- $$\boxed {a_n(2)=3.34 \mathrm{~m} / \mathrm{s}^2}$$
- ## Problema 3
  type:: problem
  unit:: 0
	- Las ecuaciones paramétricas para una partícula en movimiento son (SI):
		- $$x=t-2$$
		- $$y=t^2-t+1$$
		- Calcular:
			- a) La posición inicial de la partícula
			- b) La velocidad media en los dos primeros segundos.
			- c) La aceleración instantánea
			- d) La ecuación de la trayectoria.
	- ## Solución
	- ### Apartado a)
	- $$
	  \begin{aligned}
	  & \left.\begin{array}{l}
	  x=t-2 \\
	  y=t^2-t+2
	  \end{array}\right\} \\
	  & \vec{r}(t)=(t-2) i+\left(t^2-t+2\right) j \\
	  & \vec{r}(0)=-2 i+2 j \mathrm{~m} \\
	  & \vec{r}(2)=4 j \mathrm{~m} \\
	  & \boxed{\vec{r}(0)=(-2,2)} \\
	  &
	  \end{aligned}
	  $$
	- ### Apartado b)
		- Ahora veamos la velocidad media en los dos primeros segundos:
		- $$
		  \vec{v}_m=\frac{\Delta \vec{r}}{\Delta t}-\frac{\vec{r}(2)-\vec{r}(0)}{2}=\frac{4 j-(-2 i+2 j)}{2}=\frac{2 i+2)}{2}=i+j \mathrm{~m} / \mathrm{s}
		  $$
		- $$\boxed {\vec{v}_m=i+j \mathrm{~m} / \mathrm{s}}$$
	-
	- ### Apartado c)
		- Para la aceleración instantánea tendremos que derivar dos veces el vector posición:
		- $$
		  \begin{aligned}
		  & \vec{v}(t)=\frac{d \vec{r}(t)}{d(t)}=i+(2 t-1) j \mathrm{~m} / \mathrm{s} \\
		  & \vec{a}(t)=\frac{d \vec{v}(t)}{d t}=2 j \mathrm{~m} / \mathrm{s}^2 \enspace
		  \end{aligned}
		  $$
		- $$\boxed {\vec{a}(t)=2 j \mathrm{~m} / \mathrm{s}^2 \enspace \mathrm{cte}}$$
	- ### Apartado d)
		- La ecuación de la trayectoria la obtendremos despejando el tiempo de las ecuaciones paramétricas:
		- $$
		  \left.\begin{array}{l}
		  x=t - 2 \\
		  y=t^2-t+2
		  \end{array}\right\} \Rightarrow t=x+2
		  $$
		- $$
		  \begin{aligned}
		  & y=(x+2)^2-(x+2)+2 \\
		  & y=x^2+4+4 x-x-2+2 \\
		  & y=x^2+3 x+4
		  \end{aligned}
		  $$
		- La ecuación de la trayectoria es una parábola
		- $$\boxed {y=x^2+3 x+4}$$
- ## Problema 4
  type:: problem
  unit:: 0
	- Un perrito salta a un río y quiere llegar a la orilla contraria. La anchura del río es de $20 m$, la velocidad del perrito es de $0,2 m/s$, perpendicular a la orilla, y la corriente del río tiene una velocidad de $2 m/s$. Calcula:
		- a.- El tiempo que tarda el perrito en cruzar el río.
		  b.- Cuánto se desviará de la perpendicular al río.
		  c.- La distancia total recorrida y el vector velocidad total del perrito.
		  d.- La ecuación de la trayectoria.
	- ## Solución
		- ![image.png](../assets/image_1676559679276_0.png)
		- $$
		  \begin{aligned}
		  & V_{\text {perro }}=0^{\prime} 2 \mathrm{~m} / \mathrm{s}=0^{\prime} 2 \vec j \\
		  & V_{\text {rio }}=2 \mathrm{~m} / \mathrm{s}=2 \vec i \\
		  & y=20 \mathrm{~m}
		  \end{aligned}
		  $$
		- Se trata de un movimiento compuesto. Lo mas importante aquí es entender que cada movimiento funciona de manera independiente.
		- #### Apartado a)
			- $$
			  \begin{aligned}
			  & y=y_0+v_{\text {perro }} t \\
			  & y=2 t \\
			  & 20=0+0.2 t \\
			  & t=\frac{20}{0.2} \\
			  & \boxed {t= 100 \mathrm{~s}}
			  \end{aligned}
			  $$
		- #### Apartado b)
		-
		- $$
		  \begin{aligned}
		  & x=x_0+V_{r, 0} t \\
		  & x=0^{\prime} 2 t \\
		  & x=0+2 \cdot 100 \\
		  & \boxed{x=200 \mathrm{~m}}
		  \end{aligned}
		  $$
		- #### Apartado c)
			- $$
			  d=\sqrt{x^2+y^2}=\sqrt{20^2+200^2}=200.99 \mathrm{~m}
			  $$
			- $$
			  \boxed {\vec{v}=\vec{v}_{\text {perro }}+\vec{v}_{\text {rio}}=2 i+\frac{1}{5} j}
			  $$
		- #### Apartado d)
			- $$
			  \left.\begin{array}{l}
			  y=0.2 t \\
			  x=2 t
			  \end{array}\right\} t=\frac{x}{2}
			  $$
			- $$
			  y=0.2 \frac{x}{2}
			  $$
			- $$\boxed{y=\frac {1}{10}x}$$
- ## Problema 5
  type:: problem
  unit:: 0
	- Una barca quiere cruzar un río de $100 m$ de anchura de manera que llegue al punto que hay justo en frente de donde sale. Sus motores desarrollan una velocidad de $4m/s$, y la velocidad de la corriente rio abajo es de $3 m/s$.
		- ¿Cuál debe ser el ángulo que forme la velocidad con la perpendicular a la orilla? ¿Qué tiempo tarda en cruzar el río?
		- ¿Qué ocurriría si la velocidad de la corriente fuera mayor que la de la barca?
	- Imagina ahora que la velocidad de otra barca es perpendicular a la orilla y que la barca aparece $330 m$ corriente abajo. ¿Cuál era su velocidad?
	- ## Solución
	- ![image.png](../assets/image_1676629492216_0.png)
	- Las ecuaciones del movimiento de la barca son:
	- $$
	  \left.\left.\begin{array}{l}
	  v_{x_{\text {Barca }}}=v_{\text {Barca }} \operatorname{cos} \theta \\
	  v_{y_{\text {Barca }}}=v_{\text {Barca }} \operatorname{sen} \theta
	  \end{array}\right\} \quad \begin{array}{l}
	  x=v_{x_0}+v_{x_{\text {Barca }}} t \\
	  y=v_{y_0}+v_{y_{\text {barca }}} t
	  \end{array}\right\}
	  $$
	-
	- La barca tiene que salir desde la orilla con un ángulo determinado $\theta$ para que su movimiento sea completamente perpendicular a la orilla, osea, la componente $$\vec v_x$$ debe anular a la corriente del rio, lo cual significa que esa componante tiene que tener el mismo módulo y direccion contraria a la velocidad de la corriente del río. Por tanto:
		- $$
		  \left.\begin{array}{l}
		  v_{x_{Barca}}=v_{\text {Barca }} \cos \theta \\
		  v_{x_{\text {Barca}}}=-v_{x_{Rio}}
		  \end{array}\right\}-3=4 \cos \theta \Rightarrow \theta=\operatorname{arcos}\left(-\frac{3}{4}\right)=-48.5^{\circ}
		  $$
	-
		- $$\boxed {\theta = -48.5^{\circ}}$$
		- Veamos el tiempo que tarda en llegar:
			- $$
			  \begin{aligned}
			  y & =v_{\text {Barca}} \cdot \cos \theta t \\
			  100 & =4 \cdot \cos \left(-48.5\right) t \\
			  t & =\frac{100}{4 \cos \left(-48.5\right)}=37.7s
			  \end{aligned}
			  $$
			- $$\boxed{t=37.7s}$$
	- Si la velocidad de la corriente fuera mayor que la de la barca ($v_{Barca} < v_{x_{Rio}}$)
		- Tendríamos
		- $$v_{Barca} \leq v_{x_{Barca}}=v_{Barca} cos\theta$$
		- Ya que $cos \theta \leq 1$ y:
		- $$v_{x_{Barca}} < v_{x_{Rio}}$$
		-
	- Y por lo tanto la barca nunca llegaría al punto justo enfrente al de salida porque seria arrastrada por la corriente en dirección $x$.
	-