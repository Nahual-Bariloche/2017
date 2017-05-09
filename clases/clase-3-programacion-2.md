# Clase 3 - Programación segunda clase

## Conexión

*Tiempo estimado: 10 min*

Plantear el problema de un Robot que tiene que encontrar un objeto escondido en un laberinto. El laberinto tiene bifurcaciones y sólo puede utilizar 8 comandos. El robot tiene 7 instrucciones:
- avanzar  
- girar izq 
- girar der 
- hay camino enfrente?
- hay camino a la izq?
- hay camino a la der?
- está el objeto?

Un ejemplo en seudocódigo:

```
"repetir mientras no" encontreObjeto()
    "si" hayCaminoEnfrente()
        avanzar()
    "si" hayCaminoADerecha()
        girarDerecha()
    "si" hayCaminoAIzquierda()
        girarIzquierda()
```

La idea es que piensen sobre que no alcanzan con esas instrucciones y que necesitan una forma de preguntar / sensar (if) y una forma de repetir instrucciones (while/for). No es requisito encontrar la solución, sino sólo reflexionar sobre la necesidad de estas instrucciones.

## Concepto

**Tipos de instrucciones:**

   - comandos:
       - avanzar
       - girar
   - sensores:
       - hay camino?
       - encontré objeto?
   - control de flujo
       - pregunta / condición
       - repetir instrucciones / ciclo

## Práctica: 

- Charlar sobre estos conceptos

- Hacer ejercicios con Pilas Bloques / [Blockly](https://blockly-games.appspot.com/), en particular se puede realizar el [nivel del laberinto de blockly](https://blockly-games.appspot.com/maze)


Pasar [video Ética en la informática](https://www.youtube.com/watch?v=lYW3FoTaVLg)

## Conclusión:
*Tiempo estimado: 20 min*

 1) Preguntas/dudas, charlar brevemente sobre lo aprendido

 2) Mini retro: qué te gustó y que no y qué te gustaría ver la próxima clase, post it en el pizarrón          
 
 Que me gustó | Que no me gustó  | Que más quiero ver
 --- | --- | ---
  |  |
  |  |