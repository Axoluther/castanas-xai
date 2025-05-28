# XAI
> Próximamente
# Modelo
> * En el archivo `CNN.ipynb` se 
encuentra el modelo y su 
entrenamiento.
> * En la carpeta `modelos` se 
encuentra el modelo con más accuracy 
de los datos de validación. Puede 
haber más de uno dado a varios 
intentos por mejorar el rendimiento

# Data Augmentation
> En el archivo `data augmentation.
ipynb` se encarga de generar imagenes
artificiales a partir de las 
originales

# Datos
## [`castanas_ds`](https://github.com/Axoluther/castanas-xai/tree/main/castanas_ds)
> Imágenes sin modificación. Estructura:
```
castanas_ds/
├── comible/
└── no_comible/
```
> * Las imagenes no tienen las misma resolución cada una de ellas, y son mayores a 2000 o 3000 px.
> * Hay un total de 547 imágenes, 370 de la clase `comible` y 177 de la `no_comible`

## [`castanas_aug_ds`](https://github.com/Axoluther/castanas-xai/tree/main/castanas_aug_ds)
> Imagenes nuevas generadas a partir de las [`castanas_ds`](https://github.com/Axoluther/castanas-xai/tree/main/castanas_ds).
```
castanas_aug_ds/
├── comible/
└── no_comible/
```
> * Las imágenes tienen resolución de 256x256 px
> * Hay un total de 2186 imágenes, 1479 de la clase `comible` y 707 de `no comible`
