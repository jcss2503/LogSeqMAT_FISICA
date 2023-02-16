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