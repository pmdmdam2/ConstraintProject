# ConstraintProject

Es un ejemplo de diseño de interfaces usando ConstraintLayout. Está formado por varios LinearLayouts para dar forma de lista.

- LinearLayout principal: 
  - android:weightSum="5": peso para distriubir entre los Views contenidos
  - app:layout_constraintEnd_toEndOf="parent": ajustado a la derecha del contenedor padre
  - app:layout_constraintStart_toStartOf="parent": ajustado a la izquierda del contenedor padre
  - app:layout_constraintTop_toTopOf="parent">: ajustado a la parte superior del contenedor padre
  
- LinearLayouts de cada fila:
  -  android:layout_weight="1": peso del View en el contenedor

- Interfaz gráfica de la actividad principal, vista de diseño

![Captura del diseño de la interfaz](https://raw.githubusercontent.com/pmdmdam2/ConstraintProject/master/app/src/main/assets/constraint.png)
