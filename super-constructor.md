**What is the purpose of using super constructor with props argument?**

The purpose of using the **`super(props)`** constructor with the props argument is to call the constructor of the parent class and pass in the props. It is necessary because the parent class's constructor sets up the initial state and props of the component and must be called before the child class's constructor.