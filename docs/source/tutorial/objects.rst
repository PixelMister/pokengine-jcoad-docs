.. _objects_tutorial:

########
Objects
########

An **object** is a single 16x16 tile that holds its own special properties to add functionality to the game. The most common objects are simple, such as solid blocks (walls), ledges, or signs, but some objects can be more complex, such as doors, warps, or stairs.

A lot of objects are pre-built within the Mapbuilder already which are called **Global Objects**, making your job as a developer even easier! However, you may want to be familiar with creating your own objects in case you need to.

Code Types
==========
All objects may contain jCoad to specify their behaviour and all the jCoad in this guide can be used in the two code types detailed below.

Root Code
  Is a global code that is shared across all instances of that object placed on any map. Root code is great for code that must be repeated across multiple tiles, such as walls or shorelines. Instead of writing the code in     every object you place, you can write it just once and place that object everywhere you need that functionality.

Instance Code
  Is code exclusive to the single tile the object resides on. This code is written on a single object instance on a single map. Instance code is best for creating a unique event, such as NPC dialogue, that never needs to     be repeated.

Objects can have *both* root code and instance code. Think of a sign. All signs are solid, but most signs hold a unique message. Therefore, a sign object would probably have the following jCoad:

**Root Code Example**:
*The following code would cause a 16x16 object block to be solid in all directions.*

.. code-block::
    :caption: Root Code

    solid()

**Instance Code Example**:
*The following code would cause a 16x16 object block to hold a message, which would display when interacted with.*

.. code-block::
    :caption: Instance Code

    msg(I am a unique sign. Only I hold this message!)
