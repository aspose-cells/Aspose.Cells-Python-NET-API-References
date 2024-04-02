---
title: GridAbstractCalculationEngine clase
second_title: Aspose.Cells.GridJs for Python via .NET API Referencias
description:
type: docs
weight: 20
url: /es/aspose.cellsgridjs/gridabstractcalculationengine/
is_root: false
---
##  GridAbstractCalculationEngine clase

Representa el motor de cálculo personalizado del usuario para ampliar el motor de cálculo predeterminado de Aspose.Cells.



El tipo GridAbstractCalculationEngine expone los siguientes miembros:

###  Métodos
| Método| Descripción|
| :- | :- |
| [calculate](/cells/python-net/es/aspose.cellsgridjs/gridabstractcalculationengine/calculate/#aspose.cellsgridjs.GridCalculationData) | Calcula una función con datos dados.|



###  Observaciones


El usuario no debe modificar ninguna parte del libro de trabajo directamente en esta implementación (excepto el resultado calculado de la función personalizada, que se puede configurar mediante la propiedad GridCalculationData.CalculatedValue).
De lo contrario, se pueden producir resultados inesperados o excepciones.
Si el usuario necesita cambiar otros datos además del resultado calculado en la implementación de algunas funciones personalizadas,
Por ejemplo, cambiar la fórmula, el estilo, etc. de la celda, el usuario debe recopilar esos datos en esta implementación y cambiarlos fuera del alcance del cálculo de la fórmula.

###  Ver también
* módulo [`aspose.cellsgridjs`](..)
