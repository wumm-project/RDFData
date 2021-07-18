# Different Versions of the TRIZ Matrix

## Background

### en:

One of the central TRIZ approaches is the elaboration of a technical
contradiction, which manifests itself in the fact that the amplification of a
useful effect is accompanied by the amplification of a harmful effect. The
MATRIX classifies these effects in the form of general parameters and lists
proven general solution approaches in the form of principles for the resulting
classes of pairs of contradictions. There are several versions of this MATRIX
as well as the criticism that such a MATRIX must be regularly updated with the
development of technology. The list of parameters is also not uniform in the
different versions.

In all versions, the general approaches are extracted from the analysis of a
larger set of patents. With the "Invention Machine" and in its successors, an
attempt is made to implement this development approach as continuous process
and make it available as a tool to the engineer.

### de:

Einer der zentralen TRIZ-Ansätze ist die Herausarbeitung eines technischen
Widerspruchs, der sich darin äußert, dass die Verstärkung einer nützlichen
Wirkung von der Verstärkung einer schädlichen Wirkung begleitet wird. Mit der
MATRIX wird versucht, diese Wirkungen in der Form allgemeiner Parameter zu
klassifizieren und zu den sich so ergebenden Klassen von Widerspruchspaaren
bewährte allgemeine Lösungsansätze in der Form von Prinzipien anzugeben. Es
gibt mehrere Versionen dieser MATRIX sowie die Kritik, dass eine solche MATRIX
mit dem sich entfaltenden Stand der Technik selbst fortgeschrieben werden
muss.  Auch der Zuschnitt der Parameter ist in den verschiedenen Versionen
nicht einheitlich.

Die allgemeinen Lösungsansätze sind in allen Fällen aus der Analyse einer
größeren Menge von Patentschriften extrahiert. Mit der „Invention Machine“ und
ihren Nachfolgern wird versucht, diesen Entwicklungsansatz zu verstetigen und
als Werkzeug des Ingenieurs verfügbar zu machen.

### ru:

Одним из центральных подходов ТРИЗ является разработка технического
противоречия, которое проявляется в том, что усиление полезного эффекта
сопровождается усилением вредного эффекта. В матрице сделана попытка
классифицировать эти эффекты в виде общих параметров и указать проверенные
общие подходы к решению в виде _приемов_ для возникающих классов пар
противоречий. Существует несколько версий матрицы, а также критика, что такая
матрица должна обновляться в соответствии с разворачивающимся состоянием самой
технологии. Число и определение параметров также не является одинаковым в
различных версиях.

Во всех случаях выбор приёмов основан на анализе большого набора патентных
спецификаций. С помощью "Invention Machine" и ее преемников предпринимается
попытка динамизировать этот подход и сделать его доступным в качестве
инструмента инженера.

## Data Structure

The parameters and principles are summarised across versions in the files
_Parameters.ttl_ and _Principles.ttl_ in Turtle notation and mapped to the
numbering of the respective version of the MATRIX.

The versions of the MATRIX itself are available in JSON format as a JSON
dictionary with keys
```
attribution, title, theMatrix
```
where the value of the "theMatrix" is a list of triples
```
{improved:i, detoriated:j, recommendations:l}
```
in which i and d indicate the numbers of the respective parameters and l is a
list of the numbers of the recommended procedures.

## Matrix-1985

The data was retrieved from the `TRIZ_Matrix.xls` file that is available from
several places in the web, e.g.

- <https://www.innovation-triz.com/TRIZ40/TRIZ_Matrix.xls>
- <http://www.i-sim.org/Altshuller_Matrix.xls>

## Matrix-2003

The data was retrieved by Tom Stelze within a student's project. 
