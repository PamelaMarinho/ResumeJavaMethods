> o que estiver nessa sessão apresenta os métodos implementados e suas respectivas interfaces/classes

# OBJECT
hashCode(), equals(), clone(), toString(), notify(), notifyAll(), wait(), finalize(),  getClass()<br><br>

# COLLECTION


💠 Collection(interface) Métodos( add(obj) - addAll(collection objs) -  remove(obj) - removeAll(collection objs) - retainAll(collection obj) - clear() - isEmpty() - size() - contains(obj) - containsAll(collection) - toArray(collection), hashCode(), equals(obj))

> Iterable: <a href="https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Iterable.html#forEach(java.util.function.Consumer)">forEach</a>

<br>

## QUEUE

💠 <mark>Queue</mark> extends collection>iterable - prioridade de processamento, ordena elementos first in first out (mas não necessáriamente).

add(), offer(), remove(), poll(), peek()

> Iterator: [forEach](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Iterable.html#forEach(java.util.function.Consumer))
>
> Collection: [addAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#addAll(java.util.Collection)), [clear](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#clear()), [contains](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#contains(java.lang.Object)), [containsAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#containsAll(java.util.Collection)), [equals](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#equals(java.lang.Object)), [hashCode](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#hashCode()), [isEmpty](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#isEmpty()), [iterator](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#iterator()), [parallelStream](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#parallelStream()), [remove](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#remove(java.lang.Object)), [removeAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#removeAll(java.util.Collection)), [removeIf](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#removeIf(java.util.function.Predicate)), [retainAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#retainAll(java.util.Collection)), [size](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#size()), [spliterator](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#spliterator()), [stream](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#stream()), [toArray](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#toArray()), [toArray](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#toArray(java.util.function.IntFunction)), [toArray](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#toArray(T[]))

<br>

💠 <mark>Deque</mark> extends queue>collection>iterable

addFirst(), addLast(), offerFirst(), offerLast(), removeFirst(), removeLast(), pollFirst(), pollLast(), getFirst(), getLast(), peekFirst(), peekLast(), removeFirstOccurrence(), removeLastOccurrence(), add(), offer(), remove(), poll(), element(), peek(), addAll(), push(), pop(), remove(), contains(), size(), iterable(), descendingIterator()

> Iterable: <a href="https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Iterable.html#forEach(java.util.function.Consumer)">forEach</a>
>
> Collection: [clear](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#clear()), [containsAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#containsAll(java.util.Collection)), [equals](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#equals(java.lang.Object)), [hashCode](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#hashCode()), [isEmpty](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#isEmpty()), [parallelStream](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#parallelStream()), [removeAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#removeAll(java.util.Collection)), [removeIf](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#removeIf(java.util.function.Predicate)), [retainAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#retainAll(java.util.Collection)), [spliterator](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#spliterator()), [stream](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#stream()), [toArray](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#toArray()), [toArray](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#toArray(java.util.function.IntFunction)), [toArray](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#toArray(T[]))

<br>

## LIST


💠 <mark>List </mark>  extends Collection>iterable - coleção ordenada/permite elementos duplicados/possui indíce/permite múltiplos elementos nulos

size(),isEmpty(), contains(obj), iterator, toArray()*, add(), remove(), addAll()*, removeAll(), retainAll(), get(), set(), clear(), indexOf(), latIndexOf(), listIterator(), iterator(), spliterator(), equals(), hashCode(), sunList(), replaceAll(), sort(), copyOf, of()*, containsAll()

> Iterator: [forEach](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Iterable.html#forEach(java.util.function.Consumer))
>
> Collection: [parallelStream](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#parallelStream()), [removeIf](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#removeIf(java.util.function.Predicate)), [stream](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#stream()), [toArray](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#toArray(java.util.function.IntFunction))

<br>

💠 <mark>ArrayList</mark>   extends Collection>iterable - homogênio - tamanho fixo - não suporta métodos de leitura 

size(), isEmpty(), contains(),  iterator(), toArray(), add()*, remove(), addAll()*, removeAll(), retainAll(), get(), set(), clear(), indexOf(), latIndexOf(), listIterator(), spliterator(), equals(), hashCode(), sunList(), removeIf(),  clone(), trimToSize(), ensureCapacity(int), removeRange(), forEach()

> Object: [finalize](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#finalize()), [getClass](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#getClass()), [notify](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#notify()), [notifyAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#notifyAll()), [wait](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#wait()), [wait](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#wait(long)), [wait](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#wait(long,int))
>
> AbstractCollection: [containsAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractCollection.html#containsAll(java.util.Collection)), [toString](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractCollection.html#toString())
>
> Collection: [parallelStream](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#parallelStream()), [stream](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#stream()), [toArray](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#toArray(java.util.function.IntFunction))
>
> AbstractList: [equals](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractSet.html#equals(java.lang.Object)), [hashCode](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractSet.html#hashCode())
>
> List: [containsAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/List.html#containsAll(java.util.Collection)), [replaceAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/List.html#replaceAll(java.util.function.UnaryOperator)), [sort](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/List.html#sort(java.util.Comparator))

<br>

💠 <mark>Vector</mark>  

size(), isEmpty(), contains(), listIterator(), iterator(), equals(), addAll(), indexOf()*, toArray(), get(), set(), add(), remove(), clear(),  spliterator(), removeIf() ,   clone(),  trimToSize(),  removeRange(),  capacity(), ensureCapacity(),   hashCode()
lastIndexOf()*, removeAll(), retainAll(), containsAll(), elementAt(), firstElement(), lastElement(), toString(), subList(), setElementAt(), removeElementAt(), insertElementAt(), addElement(),  copyInto(), elements(), setSize(), removeElement(), removeAllElements(), replaceAll()

> Object: [finalize](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#finalize()), [getClass](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#getClass()), [notify](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#notify()), [notifyAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#notifyAll()), [wait](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#wait()), [wait](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#wait(long)), [wait](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#wait(long,int))
>
> Collection: [parallelStream](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#parallelStream()), [stream](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#stream()), [toArray](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#toArray(java.util.function.IntFunction))
>
> List: <a href="https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/List.html#sort(java.util.Comparator">sort</a>

<br>

💠 <mark>LInkedList</mark>   implements List e abstractSequentialList

size(), contains(), add(), remove(), addAll()*, clear(), get(), set(), indexOf(), lastIndexOf(), listIterator(),  toArray(), spliterator()
clone(), descendingIterator(), peek(), element(), poll(), offer(), offerLast(), peekFirst(), peekLast(), pollFIrst(), pollLast(), push(), pop(), removeFirstOccurrence(), removeLastOccurrence(), getFirst(), getLast(), removeFirst(), removeLast(), addFirst(), addLast()

> Iterable: [forEach](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Iterable.html#forEach(java.util.function.Consumer))
>
> Object: [finalize](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#finalize()), [getClass](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#getClass()), [notify](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#notify()), [notifyAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#notifyAll()), [wait](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#wait())
>
> AbstractCollection: [containsAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractCollection.html#containsAll(java.util.Collection)), [isEmpty](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractCollection.html#isEmpty()), [removeAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractCollection.html#removeAll(java.util.Collection)), [retainAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractCollection.html#retainAll(java.util.Collection)), [toString](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractCollection.html#toString())
>
> Collection: [parallelStream](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#parallelStream()), [removeIf](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#removeIf(java.util.function.Predicate)), [stream](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#stream()), [toArray](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#toArray(java.util.function.IntFunction))
>
> AbstractList: [equals](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractList.html#equals(java.lang.Object)), [hashCode](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractList.html#hashCode()), [listIterator](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractList.html#listIterator()), [removeRange](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractList.html#removeRange(int,int)), [subList](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractList.html#subList(int,int))
>
> List: c[ontainsAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/List.html#containsAll(java.util.Collection)), [equals](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/List.html#equals(java.lang.Object)), [hashCode](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/List.html#hashCode()), [isEmpty](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/List.html#isEmpty()), [iterator](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/List.html#iterator()), [listIterator](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/List.html#listIterator()), [removeAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/List.html#removeAll(java.util.Collection)), [replaceAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/List.html#replaceAll(java.util.function.UnaryOperator)), [retainAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/List.html#retainAll(java.util.Collection)), [sort](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/List.html#sort(java.util.Comparator)), [subList](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/List.html#subList(int,int))
>
> AbstractSequencialLIst: <a href="https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractSequentialList.html#iterator()">iterator</a>
>
> Deque: <a href="https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Deque.html#iterator()">iterator</a>
<br> 

## SET 



💠 <mark>Set</mark> - não permite elementos duplicados/não possui índice

removeAll(), size(), isEmpty(), contains(obj), iterator(), toArray(), add(e), remove(obj), containsAll(Collection), addAll(Collection), retainAll(), removeAll(), clear(), equals(), hashCode(), spliterator()
of(), copyOf()

> Iterator: [forEach](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Iterable.html#forEach(java.util.function.Consumer))
>
> Collection: [parallelStream](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#parallelStream()), [removeIf](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#removeIf(java.util.function.Predicate)), [stream](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#stream()), [toArray](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#toArray(java.util.function.IntFunction))

<br>

💠 <mark>HashSet</mark> - não mantem ordem dos elementos/permite um elemento nulo.

iterator(), size(), isEmpty(), contains(), add(), remove(), clear(), clone(), spliterator(), toArray()

>Iterator: [forEach](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Iterable.html#forEach(java.util.function.Consumer))
>
>Object: [finalize](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#finalize()), [getClass](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#getClass()), [notify](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#notify()), [notifyAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#notifyAll()), [wait](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#wait()), [wait](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#wait(long)), [wait](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#wait(long,int))
>
>AbstractCollection: [addAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractCollection.html#addAll(java.util.Collection)), [containsAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractCollection.html#containsAll(java.util.Collection)), [retainAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractCollection.html#retainAll(java.util.Collection)), [toArray](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractCollection.html#toArray()), [toArray](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractCollection.html#toArray(T[])), [toString](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractCollection.html#toString())
>
>Collection: [parallelStream](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#parallelStream()), [removeIf](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#removeIf(java.util.function.Predicate)), [stream](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#stream()), [toArray](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#toArray(java.util.function.IntFunction))
>
>AbstractSet: [equals](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractSet.html#equals(java.lang.Object)), [hashCode](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractSet.html#hashCode()), [removeAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractSet.html#removeAll(java.util.Collection))
>
>Set: [addAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Set.html#addAll(java.util.Collection)), [containsAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Set.html#containsAll(java.util.Collection)), [equals](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Set.html#equals(java.lang.Object)), [hashCode](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Set.html#hashCode()), [removeAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Set.html#removeAll(java.util.Collection)), [retainAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Set.html#retainAll(java.util.Collection))

<br>

💠 <mark>LinkedHashSet</mark>   extends HashSet - mantem ordem de inserção/permite um elemento nulo.

spliterator() 

> Iterable: [forEach](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Iterable.html#forEach(java.util.function.Consumer))
>
> Object: [finalize](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#finalize()), [getClass](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#getClass()), [notify](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#notify()), [notifyAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#notifyAll()), [wait](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#wait())
>
> AbstractCollection: [addAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractCollection.html#addAll(java.util.Collection)), [containsAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractCollection.html#containsAll(java.util.Collection)), [retainAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractCollection.html#retainAll(java.util.Collection)), [toArray](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractCollection.html#toArray()), [toArray](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractCollection.html#toArray(T[])), [toString](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractCollection.html#toString())
>
> Collection: [parallelStream](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#parallelStream()), [removeIf](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#removeIf(java.util.function.Predicate)), [stream](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#stream()), [toArray](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#toArray(java.util.function.IntFunction))
>
> AbstractSet: [equals](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractSet.html#equals(java.lang.Object)), [hashCode](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractSet.html#hashCode()), [removeAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractSet.html#removeAll(java.util.Collection))
>
> Set: add, [addAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Set.html#addAll(java.util.Collection)), [clear](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Set.html#clear()), [contains](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Set.html#contains(java.lang.Object)), [containsAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Set.html#containsAll(java.util.Collection)), [equals](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Set.html#equals(java.lang.Object)), [hashCode](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Set.html#hashCode()), [isEmpty](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Set.html#isEmpty()), [iterator](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Set.html#iterator()), [remove](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Set.html#remove(java.lang.Object)), [removeAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Set.html#removeAll(java.util.Collection)), [retainAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Set.html#retainAll(java.util.Collection)), [size](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Set.html#size()), [toArray](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Set.html#toArray()), [toArray](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Set.html#toArray(T[]))
>
> HashSet: [add](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/HashSet.html#add(E)), [clear](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/HashSet.html#clear()), [clone](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/HashSet.html#clone()), [contains](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/HashSet.html#contains(java.lang.Object)), [isEmpty](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/HashSet.html#isEmpty()), [iterator](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/HashSet.html#iterator()), [remove](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/HashSet.html#remove(java.lang.Object)), [size](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/HashSet.html#size()), [toArray](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/HashSet.html#toArray()), [toArray](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/HashSet.html#toArray(T[]))

<br>

💠 <mark>TreeSet</mark>    implements NavigableSet>SortedSet>Set - mantem ordem natural/não permite elemento nulo.

iterator(), size(), isEmpty(), contains(), add(), remove(), clear(), addAll(), clone(), spliterator()
subSet(), headSet(), tailSet(), subSet(), headSet(), tailSet(), comparator(), first(), last(), lower(), floor(), ceiling(), higher(), pollFirst(), pollLast(), descendingIterator(), descendingSet()

>Iterator: [forEach](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Iterable.html#forEach(java.util.function.Consumer))
>
>Object: [finalize](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#finalize()), [getClass](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#getClass()), [notify](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#notify()), [notifyAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#notifyAll()), [wait](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#wait()), [wait](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#wait(long)), [wait](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#wait(long,int))
>
>AbstractCollection: [containsAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractCollection.html#containsAll(java.util.Collection)), [retainAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractCollection.html#retainAll(java.util.Collection)), [toArray](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractCollection.html#toArray()), [toArray](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractCollection.html#toArray(T[])), [toString](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractCollection.html#toString())
>
>Collection: [parallelStream](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#parallelStream()), [removeIf](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#removeIf(java.util.function.Predicate)), [stream](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#stream()), [toArray](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Collection.html#toArray(java.util.function.IntFunction))
>
>AbstractSet: [equals](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractSet.html#equals(java.lang.Object)), [hashCode](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractSet.html#hashCode()), [removeAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractSet.html#removeAll(java.util.Collection))
>
>Set: [containsAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Set.html#containsAll(java.util.Collection)), [equals](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Set.html#equals(java.lang.Object)), [hashCode](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Set.html#hashCode()), [removeAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Set.html#removeAll(java.util.Collection)), [retainAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Set.html#retainAll(java.util.Collection)), [toArray](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Set.html#toArray()), [toArray](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Set.html#toArray(T[]))
<br>

# MAP


💠 <mark>Map</mark> 

size(), isEmpty(), containsKey(), containsValue(), get(), put(), remove(), putAll(), clear(), keySet(), values(), entrySet(), equals(), computeIfAbsent(), computeIfPresent(), compute(), merge(), hashCode(), getOrDefault(), forEach(), replaceAll(), outIfAbsent(), replace(),  of(), ofEntries(), entry(), copyOf()

<br>

💠 <mark>HashMap</mark> extended abstractMap>map - par key: value - key deve ser único, value pode ser duplicado 

size(), isEmpty(), containsKey(), containsValue(), get(), put(), remove(), putAll(), clear(), keySet(), values(), entrySet(), equals(), computeIfAbsent(), computeIfPresent(), compute(), merge(), clone()

> Object: [finalize](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#finalize()), [getClass](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#getClass()), [notify](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#notify()), [notifyAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#notifyAll()), [wait](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#wait()), [wait](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#wait(long)), [wait](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#wait(long,int))
>
> AbstractMap: [equals](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractMap.html#equals(java.lang.Object)), [hashCode](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractMap.html#hashCode()), [toString](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractMap.html#toString())
>
> Map: <a href="https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#equals(java.lang.Object)">equals, </a>
 <a href="https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#forEach(java.util.function.BiConsumer)">forEach, </a>
 <a href="https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#getOrDefault(java.lang.Object,V)">getOrDefault, </a>
 <a href="https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#hashCode()">hashCode, </a>
 <a href="https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#putIfAbsent(K,V)">putIfAbsent, </a>
<a href="https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#remove(java.lang.Object,java.lang.Object)">remove, </a>
 <a href="https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#replace(K,V)">replace, </a>
> <a href="https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#replace(K,V,V)">replace, </a>
 <a href="https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#replaceAll(java.util.function.BiFunction)">replaceAll</a>

<br>

💠 <mark>LinkedHashMap</mark>  extended  hashMap>abstractMap>map

containsValue(), get(), clear(), removeEldestEntry(), keySet(), values(), entrySet()

> Object: [finalize](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#finalize()), [getClass](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#getClass()), [notify](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#notify()), [notifyAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#notifyAll()), [wait](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#wait()), [wait](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#wait(long)), [wait](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#wait(long,int))
>
> AbstractMap: [equals](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractMap.html#equals(java.lang.Object)), [hashCode](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractMap.html#hashCode()), [toString](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractMap.html#toString())
>
> Map: [compute](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#compute(K,java.util.function.BiFunction)), [computeIfAbsent](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#computeIfAbsent(K,java.util.function.Function)), [computeIfPresent](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#computeIfPresent(K,java.util.function.BiFunction)), [containsKey](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#containsKey(java.lang.Object)), [equals](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#equals(java.lang.Object)), [forEach](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#forEach(java.util.function.BiConsumer)), [getOrDefault](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#getOrDefault(java.lang.Object,V)), [hashCode](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#hashCode()), [isEmpty](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#isEmpty()), [merge](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#merge(K,V,java.util.function.BiFunction)), [put](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#put(K,V)), [putAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#putAll(java.util.Map)), [putIfAbsent](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#putIfAbsent(K,V)), [remove](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#remove(java.lang.Object)), [remove](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#remove(java.lang.Object,java.lang.Object)), [replace](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#replace(K,V)), [replace](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#replace(K,V,V)), [replaceAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#replaceAll(java.util.function.BiFunction)), [size](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#size())
>
> HashMap: [clear](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/HashMap.html#clear()), [clone](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/HashMap.html#clone()), [compute](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/HashMap.html#compute(K,java.util.function.BiFunction)), [computeIfAbsent](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/HashMap.html#computeIfAbsent(K,java.util.function.Function)), [computeIfPresent](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/HashMap.html#computeIfPresent(K,java.util.function.BiFunction)), [containsKey](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/HashMap.html#containsKey(java.lang.Object)), [isEmpty](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/HashMap.html#isEmpty()), [merge](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/HashMap.html#merge(K,V,java.util.function.BiFunction)), [put](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/HashMap.html#put(K,V)), [putAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/HashMap.html#putAll(java.util.Map)), [remove](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/HashMap.html#remove(java.lang.Object)), [size](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/HashMap.html#size())

<br>

💠 <mark>TreeMap</mark> implements  sortedMap>navigateMap

size(), containsKey(), containsValue(), get(), comparator(), firstKey(), lastKey(), putAll(), put(), computeIfAbsent(), computeIfPresent(), compute(), merge(), remove(), clear(), clone(), firstEntry(), lastEntry(), pollFirstEntry(), pollLastEntry(), lowerEntry(), lowerKey(), floorEntry(), floorkey(), ceilingEntry(), ceilingkey(), heigherEntry(), higherkey(), keySet(), navigablekeySet(), descendingKeySet(), values(), entrySet(), descendingMap(), subMap(), heaMap(), tailMap(), subMap(), headMap(), tailMap()

> Object: [finalize](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#finalize()), [getClass](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#getClass()), [notify](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#notify()), [notifyAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#notifyAll()), [wait](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#wait()), [wait](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#wait(long)), [wait](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Object.html#wait(long,int))
>
> AbstractMap: [equals](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractMap.html#equals(java.lang.Object)), [hashCode](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractMap.html#hashCode()), [toString](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/AbstractMap.html#toString())
>
> Map: [equals](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#equals(java.lang.Object)), [forEach](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#forEach(java.util.function.BiConsumer)), [getOrDefault](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#getOrDefault(java.lang.Object,V)), [hashCode](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#hashCode()), [isEmpty](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#isEmpty()), [putIfAbsent](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#putIfAbsent(K,V)), [remove](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#remove(java.lang.Object,java.lang.Object)), [replace](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#replace(K,V)), [replace](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#replace(K,V,V)), [replaceAll](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Map.html#replaceAll(java.util.function.BiFunction))

