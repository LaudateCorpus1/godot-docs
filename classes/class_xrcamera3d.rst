:github_url: hide

.. Generated automatically by doc/tools/make_rst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the XRCamera3D.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_XRCamera3D:

XRCamera3D
==========

**Inherits:** :ref:`Camera3D<class_Camera3D>` **<** :ref:`Node3D<class_Node3D>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

A camera node with a few overrules for AR/VR applied, such as location tracking.

Description
-----------

This is a helper spatial node for our camera; note that, if stereoscopic rendering is applicable (VR-HMD), most of the camera properties are ignored, as the HMD information overrides them. The only properties that can be trusted are the near and far planes.

The position and orientation of this node is automatically updated by the XR Server to represent the location of the HMD if such tracking is available and can thus be used by game logic. Note that, in contrast to the XR Controller, the render thread has access to the most up-to-date tracking data of the HMD and the location of the XRCamera3D can lag a few milliseconds behind what is used for rendering as a result.

Tutorials
---------

- :doc:`VR documentation index <../tutorials/vr/index>`

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`
