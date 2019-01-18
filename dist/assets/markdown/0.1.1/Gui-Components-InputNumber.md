Gui\Components\InputNumber
===============

This is the InputNumber Class

It is a visual component for input numbers -- integer and float


* Class name: InputNumber
* Namespace: Gui\Components
* Parent class: Gui\Components\VisualObject





Properties
----------


### $lazIntClass

    protected string $lazIntClass = 'TSpinEdit'

The lazarus class string to integer number control.



* Visibility: **protected**


### $lazFloatClass

    protected string $lazFloatClass = 'TFloatSpinEdit'

The lazarus class string to float number control.



* Visibility: **protected**


### $lazarusClass

    protected string $lazarusClass = 'TObject'

The lazarus class as string



* Visibility: **protected**


### $lazarusObjectId

    protected integer $lazarusObjectId

The communication object id



* Visibility: **protected**


### $application

    protected \Gui\Application $application

The application object



* Visibility: **protected**


### $eventHandlers

    protected array $eventHandlers = array()

The array of callbacks



* Visibility: **protected**


### $runTimeProperties

    protected array $runTimeProperties = array()

The array of special properties



* Visibility: **protected**


Methods
-------


### __construct

    void Gui\Components\AbstractObject::__construct(array $defaultAttributes, \Gui\Components\ContainerObjectInterface $parent, \Gui\Application $application)

The constructor



* Visibility: **public**
* This method is defined by Gui\Components\AbstractObject


#### Arguments
* $defaultAttributes **array**
* $parent **Gui\Components\ContainerObjectInterface**
* $application **Gui\Application**



### setIncrement

    \Gui\Components\InputNumber Gui\Components\InputNumber::setIncrement(integer|float $value)

Sets the value by which the value of the control should be
increased/decresed when the user clicks one of the arrows or one of the keyboard up/down arrows.



* Visibility: **public**


#### Arguments
* $value **integer|float**



### getIncrement

    integer|float Gui\Components\InputNumber::getIncrement($value)

Gets the value by which the value of the control should be
increased/decresed when the user clicks one of the arrows or one of the keyboard up/down arrows.



* Visibility: **public**


#### Arguments
* $value **mixed**



### setMax

    \Gui\Components\InputNumber Gui\Components\InputNumber::setMax(integer|float $max)

Sets de max value.



* Visibility: **public**


#### Arguments
* $max **integer|float**



### getMax

    integer|float Gui\Components\InputNumber::getMax()

Gets the max value.



* Visibility: **public**




### setMin

    \Gui\Components\InputNumber Gui\Components\InputNumber::setMin(integer|float $min)

Sets de min value.



* Visibility: **public**


#### Arguments
* $min **integer|float**



### getMin

    integer|float Gui\Components\InputNumber::getMin()

Gets the min value.



* Visibility: **public**




### setValue

    \Gui\Components\InputNumber Gui\Components\InputNumber::setValue(integer|float $value)

Sets the value of value.



* Visibility: **public**


#### Arguments
* $value **integer|float**



### getValue

    integer|float Gui\Components\InputNumber::getValue()

Gets the value of value;



* Visibility: **public**




### setDecimals

    \Gui\Components\InputNumber Gui\Components\InputNumber::setDecimals(integer $decimal)

Sets decimals for control.



* Visibility: **public**


#### Arguments
* $decimal **integer**



### getDecimals

    integer Gui\Components\InputNumber::getDecimals()

Gest de decimal.



* Visibility: **public**




### getAutoSize

    Boolean Gui\Components\VisualObjectInterface::getAutoSize()

Get the auto size



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface




### setAutoSize

    \Gui\Components\VisualObjectInterface Gui\Components\VisualObjectInterface::setAutoSize(Boolean $autoSize)

Set the auto size



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface


#### Arguments
* $autoSize **Boolean**



### getBackgroundColor

    String Gui\Components\VisualObjectInterface::getBackgroundColor()

Get the background color



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface




### setBackgroundColor

    \Gui\Components\VisualObjectInterface Gui\Components\VisualObjectInterface::setBackgroundColor(string $color)

Set the background Color



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface


#### Arguments
* $color **string**



### getBottom

    integer Gui\Components\VisualObjectInterface::getBottom()

Gets the value of bottom in pixel.



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface




### setBottom

    \Gui\Components\VisualObjectInterface Gui\Components\VisualObjectInterface::setBottom(integer $bottom)

Sets the value of bottom in pixel.



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface


#### Arguments
* $bottom **integer**



### getHeight

    integer Gui\Components\VisualObjectInterface::getHeight()

Gets the value of height in pixel.



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface




### setHeight

    \Gui\Components\VisualObjectInterface Gui\Components\VisualObjectInterface::setHeight(integer $height)

Sets the value of height in pixel.



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface


#### Arguments
* $height **integer**



### getLeft

    integer Gui\Components\VisualObjectInterface::getLeft()

Gets the value of left in pixel.



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface




### setLeft

    \Gui\Components\VisualObjectInterface Gui\Components\VisualObjectInterface::setLeft(integer $left)

Sets the value of left in pixel.



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface


#### Arguments
* $left **integer**



### getRight

    integer Gui\Components\VisualObjectInterface::getRight()

Gets the value of right in pixel.



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface




### setRight

    \Gui\Components\VisualObjectInterface Gui\Components\VisualObjectInterface::setRight(integer $right)

Sets the value of right in pixel.



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface


#### Arguments
* $right **integer**



### getTop

    integer Gui\Components\VisualObjectInterface::getTop()

Gets the value of top in pixel.



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface




### setTop

    \Gui\Components\VisualObjectInterface Gui\Components\VisualObjectInterface::setTop(integer $top)

Sets the value of top in pixel.



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface


#### Arguments
* $top **integer**



### getWidth

    integer Gui\Components\VisualObjectInterface::getWidth()

Gets the value of width in pixel.



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface




### setWidth

    \Gui\Components\VisualObjectInterface Gui\Components\VisualObjectInterface::setWidth(integer $width)

Sets the value of width in pixel.



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface


#### Arguments
* $width **integer**



### getVisible

    boolean Gui\Components\VisualObjectInterface::getVisible()

Gets the value of visible in pixel.



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface




### setVisible

    \Gui\Components\VisualObjectInterface Gui\Components\VisualObjectInterface::setVisible(boolean $visible)

Sets the value of visible in pixel.



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface


#### Arguments
* $visible **boolean**



### __call

    self|mixed Gui\Components\AbstractObject::__call(string $method, array $params)

The special method used to do the getters/setters for special properties



* Visibility: **public**
* This method is defined by Gui\Components\AbstractObject


#### Arguments
* $method **string**
* $params **array**



### call

    void Gui\Components\AbstractObject::call(string $method, array $params, boolean $isCommand)

This method is used to send an object command/envent to lazarus



* Visibility: **protected**
* This method is defined by Gui\Components\AbstractObject


#### Arguments
* $method **string**
* $params **array**
* $isCommand **boolean**



### set

    void Gui\Components\AbstractObject::set(string $name, mixed $value)

this method is used to send the IPC message when a property is set



* Visibility: **protected**
* This method is defined by Gui\Components\AbstractObject


#### Arguments
* $name **string**
* $value **mixed**



### get

    mixed Gui\Components\AbstractObject::get(string $name)

This magic method is used to send the IPC message when a property is get



* Visibility: **protected**
* This method is defined by Gui\Components\AbstractObject


#### Arguments
* $name **string**



### getLazarusObjectId

    mixed Gui\Components\LazarusObjectInterface::getLazarusObjectId()

Gets the value of lazarusObjectId.



* Visibility: **public**
* This method is defined by Gui\Components\LazarusObjectInterface




### getLazarusClass

    mixed Gui\Components\LazarusObjectInterface::getLazarusClass()

Gets the value of lazarusClass.



* Visibility: **public**
* This method is defined by Gui\Components\LazarusObjectInterface




### fire

    void Gui\Components\LazarusObjectInterface::fire(string $eventName)

Fire an object event



* Visibility: **public**
* This method is defined by Gui\Components\LazarusObjectInterface


#### Arguments
* $eventName **string**



### on

    void Gui\Components\LazarusObjectInterface::on(string $eventName, callable $eventHandler)

Add a listener to an event



* Visibility: **public**
* This method is defined by Gui\Components\LazarusObjectInterface


#### Arguments
* $eventName **string**
* $eventHandler **callable**

