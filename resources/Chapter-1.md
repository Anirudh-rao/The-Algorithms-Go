# Data Structures and Algorithms in Golang

## Introduction:

A datastructure is the organization of data to reduce the storage space used and to reduce the difficulty whiler performing differnet tasks.

In this section we will cvoer the definition of abstarct datatypes , classifiying data structures into linear, nonlinear , homogenous, heterogenous and dynamic types. 

Abstract datatypes such as containers , List, Set, Map, Graph, Stack and Queue are presented in this chapter. We will also cover the performacne analysis of the data structues choosing the right data structures and structural desigh patterns.

## Classification of Datastructures and Structural Design Patterns:

The term Data structures refers to the organization of data in an computers memory, in order to retrive it quickyl for processing. Its a schema for data organization to decouple the functional definition of data structure from its implementaiton. 

The classification of data structure is as follows:

| Linear   | Non-Linear | Homogenous   | Hetrogenous |Hetrogenous |
| -------- | -----------|--------------|-------------|------------|       
| Lists    | Trees      | 2D Array     |Linked List  |Dictonaries |
| Sets     | Tables     | Multi-Array  |Ordered List |TreeSets    |
| Tuples   | Containers |              |Unordered List|Sequences  |
| Queues   |
| Stacks   |
| Heaps    |


### 1. Lists:

Lists is the sequence of elements. Each element can be connected with another with a link  in the forward or backward direction.This data structure is a basic type of container. List have variable length and eveloper can remove and add elements more easily than an array.


### 2. Tuples

A Tuple is a finite sorted list of elements. Its is a data structure that groups data. Tuples are typically immutable collections.The element has related fields of different data types.The only modify a tuple is to change the fields.Operaters like `+` and `*` can be applied to tuples. A database record is refered to as a tuple.


### 3. Heaps

A Heap is a data structure that is based on the heap property. The heap data structure is used in selection, graph, and k-way merge algorithms. Operations such as finding , merging,insertion, key changes and deleting are performed on heaps. According to the heap order (maximum heap) property, the value stored at each node is greater than or equal to its children.

## Structural design patterns:

Structural design patterns describe the relationship between entities. They are used to form large structures using classes and objects. These patterns are used to create a system with different  system blocks in a flexible manner. Adapter, Bridge, Composite ,Decorator , facade , flyweight, private class data and proxy are the **Gang Of Four(GoF)** structural design patterns. 

### Adapter

The Adapter pattern provides a wrapper with an interface required by the API client to link incompatible types and act as a trasnaltor between the two types.
