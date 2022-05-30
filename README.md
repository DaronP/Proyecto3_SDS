# Proyecto3_SDS

Cristopher Barrios
Sebastian Recinos
Jorge Perez

## Parte 1

- Accuracy del modelo original: 97.53%
- ROC AUC del modelo original: 95.46%
- Copycat CNN  model trained with 2000 entries:  81.84 %
- Knockoff Nets  model trained with 2000 entries:  78.61 %
- Protected vs Copycat  model trained with 2000 entries:  0.29 %
- Protected vs Knockoff  model trained with 2000 entries:  0.78 %

### Conclusiones
- A pesar de que los modelos CopycatCNN y KnockoffNets (sin proteccion) tuvieron un accuracy mas bajo que el modelo original, este accuracy es aceptable empresarialmente, ya que estos se encuentran arriba del 50%, siendo 78% el mas bajo.
- Los modelos robados (CopycatCNN y KnockoffNets) extraen satisfactoriamente el modelo original.
- El modelo CopycatCNN tiene mejor accuracy que el modelo KnockoffNets.
- Al proteger el modelo original, el accuracy de ambos modelos baja a menos del 1% lo que significa que al proteger el modelo, esta proteccion no deja entrenar a los modelos malignos causando un underfitting y sean ineficaces e incapaces de predecir.


## Parte 2
- Accuracy en modelo original: 92.57%
- Test accuracy con datos adversarios en modelo original: 9.08%
- Correctas:  93 
- Incorrectas:  931
- Test accuracy con datos adversarios en modelo robusto: 83.98%
- ROC AUC on adversarial samples: 95.84%
- Correctas:  860 
- Incorrectas:  164
- Test accuracy con datos limpios en modelo robusto: 86.82%
- ROC AUC on clean samples: 95.70%
- Correctas:  889 Incorrectas:  135
