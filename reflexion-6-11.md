1)
Es la forma más rápida de identificar al "dueño" o experto de un módulo. Si necesitas cambiar algo complejo, miras quién lo escribió para pedirle una revisión de código o que te explique la lógica detrás de esa implementación.
2)
Usar git blame para buscar culpables es contraproducente porque destruye la confianza y fomenta una cultura de miedo. Si el equipo siente que cada error será usado en su contra, dejarán de proponer soluciones innovadoras o de admitir fallos, lo que ralentiza el aprendizaje y empeora la calidad del software.
3)
Cada commit debe resolver una sola cosa (un bug, una funcionalidad o una refactorización). Si mezclas cambios de lógica con arreglos de estilo, el blame mostrará tu nombre en líneas que quizás no entiendes, ocultando al autor original de la lógica. Los commits atómicos permiten que el historial cuente una historia clara de la evolución del código.
