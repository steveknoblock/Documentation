-----------------------
Omeka_Form_DisplayGroup
-----------------------

.. php:class:: Omeka_Form_DisplayGroup

    Package: :doc:`Form </Reference/packages/Form/index>`

    Subclass of Zend_Form_DisplayGroup that exist to override the default 
    decorators associated with display groups.

    .. php:method:: loadDefaultDecorators()
    
        Cause display groups to render as HTML fieldset elements.
        
        :returns: void