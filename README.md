# android-suma

Para realizar este ejericio se ha seguido la guía del Curso de Android Studio, en la cual se ha usado elementos como:
- Widgets 
   - EditText
   - TextView
   - Button

Se ha implementando como menciona la guía la funcion void llamada Suma donde capturamos los valores de los text y posteriormente transformamos estos string a tipo int para poder realizar el calculo matemático. 

```javascript
 public void sumar (View view){
        String valor1= et1.getText().toString();
        String valor2= et2.getText().toString();
        int nro1=Integer.parseInt(valor1);
        int nro2=Integer.parseInt(valor2);
        int suma = nro1 + nro2;
        String resu = String.valueOf(suma);
        tv3.setText(resu);
    }
```

La interfaz de la aplicación se visualiza de la siguiente manera: 

![App Screenshot](https://raw.githubusercontent.com/CarlosMaldonado1998/android-suma/master/Images/image.png)

