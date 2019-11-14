# DePHP

│   .gitignore   
│   .travis.yml   
│   composer.json   
│   composer.lock   
│   conf.py   
│   LICENSE   
│   make.bat   
│   Makefile   
│   phpunit.xml.dist   
│   README.md   
│   README.rst   
│   README_.md   
│   Vagrantfile   
│      
├───ansible   
│   │   playbook.yml   
│   │   windows.sh   
│   │      
│   ├───inventories   
│   │       dev   
│   │          
│   ├───roles   
│   │   ├───app   
│   │   │   └───tasks   
│   │   │           main.yml   
│   │   │              
│   │   ├───composer   
│   │   │   └───tasks   
│   │   │           main.yml   
│   │   │              
│   │   ├───php   
│   │   │   └───tasks   
│   │   │           configure.yml   
│   │   │           main.yml   
│   │   │           php-cli.yml   
│   │   │              
│   │   ├───server   
│   │   │   ├───tasks   
│   │   │   │       main.yml   
│   │   │   │          
│   │   │   └───templates   
│   │   │           timezone.tpl   
│   │   │              
│   │   ├───vagrant_local   
│   │   │   └───tasks   
│   │   │           main.yml   
│   │   │              
│   │   └───xdebug   
│   │       ├───defaults   
│   │       │       main.yml   
│   │       │          
│   │       └───tasks   
│   │               main.yml   
│   │                  
│   └───vars   
│           all.yml   
│              
├───Behavioral   
│   │   README.md   
│   │   README.rst   
│   │      
│   ├───ChainOfResponsibilities   
│   │   │   Handler.php   
│   │   │   README.rst   
│   │   │      
│   │   ├───Responsible   
│   │   │       HttpInMemoryCacheHandler.php   
│   │   │       SlowDatabaseHandler.php   
│   │   │          
│   │   ├───Tests   
│   │   │       ChainTest.php   
│   │   │          
│   │   └───uml   
│   │           ChainOfResponsibilities.uml   
│   │           uml.png   
│   │           uml.svg   
│   │              
│   ├───Command   
│   │   │   AddMessageDateCommand.php   
│   │   │   CommandInterface.php   
│   │   │   HelloCommand.php   
│   │   │   Invoker.php   
│   │   │   README.rst   
│   │   │   Receiver.php   
│   │   │   UndoableCommandInterface.php   
│   │   │      
│   │   ├───Tests   
│   │   │       CommandTest.php   
│   │   │       UndoableCommandTest.php   
│   │   │          
│   │   └───uml   
│   │           Command.uml   
│   │           uml.png   
│   │           uml.svg   
│   │              
│   ├───Iterator   
│   │   │   Book.php   
│   │   │   BookList.php   
│   │   │   README.rst   
│   │   │      
│   │   ├───Tests   
│   │   │       IteratorTest.php   
│   │   │          
│   │   └───uml   
│   │           Iterator.uml   
│   │           uml.png   
│   │           uml.svg   
│   │              
│   ├───Mediator   
│   │   │   Colleague.php   
│   │   │   Mediator.php   
│   │   │   MediatorInterface.php   
│   │   │   README.rst   
│   │   │      
│   │   ├───Subsystem   
│   │   │       Client.php   
│   │   │       Database.php   
│   │   │       Server.php   
│   │   │          
│   │   ├───Tests   
│   │   │       MediatorTest.php   
│   │   │          
│   │   └───uml   
│   │           Mediator.uml   
│   │           uml.png   
│   │           uml.svg   
│   │              
│   ├───Memento   
│   │   │   Memento.php   
│   │   │   README.rst   
│   │   │   State.php   
│   │   │   Ticket.php   
│   │   │      
│   │   ├───Tests   
│   │   │       MementoTest.php   
│   │   │          
│   │   └───uml   
│   │           Memento.uml   
│   │           uml.png   
│   │           uml.svg   
│   │              
│   ├───NullObject   
│   │   │   LoggerInterface.php   
│   │   │   NullLogger.php   
│   │   │   PrintLogger.php   
│   │   │   README.rst   
│   │   │   Service.php   
│   │   │      
│   │   ├───Tests   
│   │   │       LoggerTest.php   
│   │   │          
│   │   └───uml   
│   │           NullObject.uml   
│   │           uml.png   
│   │           uml.svg   
│   │              
│   ├───Observer   
│   │   │   README.rst   
│   │   │   User.php   
│   │   │   UserObserver.php   
│   │   │      
│   │   ├───Tests   
│   │   │       ObserverTest.php   
│   │   │          
│   │   └───uml   
│   │           Observer.uml   
│   │           uml.png   
│   │           uml.svg   
│   │              
│   ├───Specification   
│   │   │   AndSpecification.php   
│   │   │   Item.php   
│   │   │   NotSpecification.php   
│   │   │   OrSpecification.php   
│   │   │   PriceSpecification.php   
│   │   │   README.rst   
│   │   │   SpecificationInterface.php   
│   │   │      
│   │   ├───Tests   
│   │   │       SpecificationTest.php   
│   │   │          
│   │   └───uml   
│   │           Specification.uml   
│   │           uml.png   
│   │           uml.svg   
│   │              
│   ├───State   
│   │   │   CreateOrder.php   
│   │   │   Order.php   
│   │   │   OrderRepository.php   
│   │   │   README.rst   
│   │   │   ShippingOrder.php   
│   │   │      
│   │   ├───Tests   
│   │   │       StateTest.php   
│   │   │          
│   │   └───uml   
│   │           State.uml   
│   │           uml.png   
│   │           uml.svg   
│   │              
│   ├───Strategy   
│   │   │   ComparatorInterface.php   
│   │   │   DateComparator.php   
│   │   │   IdComparator.php   
│   │   │   ObjectCollection.php   
│   │   │   README.rst   
│   │   │      
│   │   ├───Tests   
│   │   │       StrategyTest.php   
│   │   │          
│   │   └───uml   
│   │           Strategy.uml   
│   │           uml.png   
│   │           uml.svg   
│   │              
│   ├───TemplateMethod   
│   │   │   BeachJourney.php   
│   │   │   CityJourney.php   
│   │   │   Journey.php   
│   │   │   README.rst   
│   │   │      
│   │   ├───Tests   
│   │   │       JourneyTest.php   
│   │   │          
│   │   └───uml   
│   │           TemplateMethod.uml   
│   │           uml.png   
│   │           uml.svg   
│   │              
│   └───Visitor   
│       │   Group.php   
│       │   README.rst   
│       │   Role.php   
│       │   RoleVisitor.php   
│       │   RoleVisitorInterface.php   
│       │   User.php   
│       │      
│       ├───Tests   
│       │       VisitorTest.php   
│       │          
│       └───uml   
│               uml.png   
│               uml.svg   
│               Visitor.uml   
│                  
├───Creational   
│   │   README.md   
│   │   README.rst   
│   │      
│   ├───AbstractFactory   
│   │   │   AbstractFactory.php   
│   │   │   HtmlFactory.php   
│   │   │   HtmlText.php   
│   │   │   JsonFactory.php   
│   │   │   JsonText.php   
│   │   │   README.rst   
│   │   │   Text.php   
│   │   │      
│   │   ├───Tests   
│   │   │       AbstractFactoryTest.php   
│   │   │          
│   │   └───uml   
│   │           AbstractFactory.uml   
│   │           uml.png   
│   │           uml.svg   
│   │              
│   ├───Builder   
│   │   │   BuilderInterface.php   
│   │   │   CarBuilder.php   
│   │   │   Director.php   
│   │   │   README.rst   
│   │   │   TruckBuilder.php   
│   │   │      
│   │   ├───Parts   
│   │   │       Car.php   
│   │   │       Door.php   
│   │   │       Engine.php   
│   │   │       Truck.php   
│   │   │       Vehicle.php   
│   │   │       Wheel.php   
│   │   │          
│   │   ├───Tests   
│   │   │       DirectorTest.php   
│   │   │          
│   │   └───uml   
│   │           Builder.uml   
│   │           uml.png   
│   │           uml.svg   
│   │              
│   ├───FactoryMethod   
│   │   │   Bicycle.php   
│   │   │   CarFerrari.php   
│   │   │   CarMercedes.php   
│   │   │   FactoryMethod.php   
│   │   │   GermanFactory.php   
│   │   │   ItalianFactory.php   
│   │   │   README.rst   
│   │   │   VehicleInterface.php   
│   │   │      
│   │   ├───Tests   
│   │   │       FactoryMethodTest.php   
│   │   │          
│   │   └───uml   
│   │           FactoryMethod.uml   
│   │           uml.png   
│   │           uml.svg   
│   │              
│   ├───Multiton   
│   │   │   Multiton.php   
│   │   │   README.rst   
│   │   │      
│   │   ├───Tests   
│   │   │       MultitonTest.php   
│   │   │          
│   │   └───uml   
│   │           Multiton.uml   
│   │           uml.png   
│   │           uml.svg   
│   │              
│   ├───Pool   
│   │   │   README.rst   
│   │   │   StringReverseWorker.php   
│   │   │   WorkerPool.php   
│   │   │      
│   │   ├───Tests   
│   │   │       PoolTest.php   
│   │   │          
│   │   └───uml   
│   │           Pool.uml   
│   │           uml.png   
│   │           uml.svg   
│   │              
│   ├───Prototype   
│   │   │   BarBookPrototype.php   
│   │   │   BookPrototype.php   
│   │   │   FooBookPrototype.php   
│   │   │   README.rst   
│   │   │      
│   │   ├───Tests   
│   │   │       PrototypeTest.php   
│   │   │          
│   │   └───uml   
│   │           Prototype.uml   
│   │           uml.png   
│   │           uml.svg   
│   │              
│   ├───SimpleFactory   
│   │   │   Bicycle.php   
│   │   │   README.rst   
│   │   │   SimpleFactory.php   
│   │   │      
│   │   ├───Tests   
│   │   │       SimpleFactoryTest.php   
│   │   │          
│   │   └───uml   
│   │           SimpleFactory.uml   
│   │           uml.png   
│   │           uml.svg   
│   │              
│   ├───Singleton   
│   │   │   README.rst   
│   │   │   Singleton.php   
│   │   │      
│   │   ├───Tests   
│   │   │       SingletonTest.php   
│   │   │          
│   │   └───uml   
│   │           Singleton.uml   
│   │           uml.png   
│   │           uml.svg   
│   │              
│   └───StaticFactory   
│       │   FormatNumber.php   
│       │   FormatString.php   
│       │   FormatterInterface.php   
│       │   README.rst   
│       │   StaticFactory.php   
│       │      
│       ├───Tests   
│       │       StaticFactoryTest.php   
│       │          
│       └───uml   
│               StaticFactory.uml   
│               uml.png   
│               uml.svg   
│                  
├───locale   
│   ├───ca   
│   │   └───LC_MESSAGES   
│   │       │   README.po   
│   │       │      
│   │       ├───Behavioral   
│   │       │   │   README.po   
│   │       │   │      
│   │       │   ├───ChainOfResponsibilities   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Command   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Iterator   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Mediator   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Memento   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───NullObject   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Observer   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Specification   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───State   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Strategy   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───TemplateMethod   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   └───Visitor   
│   │       │           README.po   
│   │       │              
│   │       ├───Creational   
│   │       │   │   README.po   
│   │       │   │      
│   │       │   ├───AbstractFactory   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Builder   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───FactoryMethod   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Multiton   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Pool   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Prototype   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───SimpleFactory   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Singleton   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   └───StaticFactory   
│   │       │           README.po   
│   │       │              
│   │       ├───More   
│   │       │   │   README.po   
│   │       │   │      
│   │       │   ├───Delegation   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───EAV   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Repository   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   └───ServiceLocator   
│   │       │           README.po   
│   │       │              
│   │       └───Structural   
│   │           │   README.po   
│   │           │      
│   │           ├───Adapter   
│   │           │       README.po   
│   │           │          
│   │           ├───Bridge   
│   │           │       README.po   
│   │           │          
│   │           ├───Composite   
│   │           │       README.po   
│   │           │          
│   │           ├───DataMapper   
│   │           │       README.po   
│   │           │          
│   │           ├───Decorator   
│   │           │       README.po   
│   │           │          
│   │           ├───DependencyInjection   
│   │           │       README.po   
│   │           │          
│   │           ├───Facade   
│   │           │       README.po   
│   │           │          
│   │           ├───FluentInterface   
│   │           │       README.po   
│   │           │          
│   │           ├───Flyweight   
│   │           │       README.po   
│   │           │          
│   │           ├───Proxy   
│   │           │       README.po   
│   │           │          
│   │           └───Registry   
│   │                   README.po   
│   │                      
│   ├───de   
│   │   └───LC_MESSAGES   
│   │       │   README.po   
│   │       │      
│   │       ├───Behavioral   
│   │       │   │   README.po   
│   │       │   │      
│   │       │   ├───ChainOfResponsibilities   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Command   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Iterator   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Mediator   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Memento   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───NullObject   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Observer   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Specification   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───State   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Strategy   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───TemplateMethod   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   └───Visitor   
│   │       │           README.po   
│   │       │              
│   │       ├───Creational   
│   │       │   │   README.po   
│   │       │   │      
│   │       │   ├───AbstractFactory   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Builder   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───FactoryMethod   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Multiton   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Pool   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Prototype   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───SimpleFactory   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Singleton   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   └───StaticFactory   
│   │       │           README.po   
│   │       │              
│   │       ├───More   
│   │       │   │   README.po   
│   │       │   │      
│   │       │   ├───Delegation   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───EAV   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Repository   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   └───ServiceLocator   
│   │       │           README.po   
│   │       │              
│   │       └───Structural   
│   │           │   README.po   
│   │           │      
│   │           ├───Adapter   
│   │           │       README.po   
│   │           │          
│   │           ├───Bridge   
│   │           │       README.po   
│   │           │          
│   │           ├───Composite   
│   │           │       README.po   
│   │           │          
│   │           ├───DataMapper   
│   │           │       README.po   
│   │           │          
│   │           ├───Decorator   
│   │           │       README.po   
│   │           │          
│   │           ├───DependencyInjection   
│   │           │       README.po   
│   │           │          
│   │           ├───Facade   
│   │           │       README.po   
│   │           │          
│   │           ├───FluentInterface   
│   │           │       README.po   
│   │           │          
│   │           ├───Flyweight   
│   │           │       README.po   
│   │           │          
│   │           ├───Proxy   
│   │           │       README.po   
│   │           │          
│   │           └───Registry   
│   │                   README.po   
│   │                      
│   ├───es   
│   │   └───LC_MESSAGES   
│   │       │   README.po   
│   │       │      
│   │       ├───Behavioral   
│   │       │   │   README.po   
│   │       │   │      
│   │       │   ├───ChainOfResponsibilities   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Command   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Iterator   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Mediator   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Memento   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───NullObject   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Observer   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Specification   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───State   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Strategy   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───TemplateMethod   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   └───Visitor   
│   │       │           README.po   
│   │       │              
│   │       ├───Creational   
│   │       │   │   README.po   
│   │       │   │      
│   │       │   ├───AbstractFactory   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Builder   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───FactoryMethod   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Multiton   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Pool   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Prototype   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───SimpleFactory   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Singleton   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   └───StaticFactory   
│   │       │           README.po   
│   │       │              
│   │       ├───More   
│   │       │   │   README.po   
│   │       │   │      
│   │       │   ├───Delegation   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───EAV   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Repository   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   └───ServiceLocator   
│   │       │           README.po   
│   │       │              
│   │       └───Structural   
│   │           │   README.po   
│   │           │      
│   │           ├───Adapter   
│   │           │       README.po   
│   │           │          
│   │           ├───Bridge   
│   │           │       README.po   
│   │           │          
│   │           ├───Composite   
│   │           │       README.po   
│   │           │          
│   │           ├───DataMapper   
│   │           │       README.po   
│   │           │          
│   │           ├───Decorator   
│   │           │       README.po   
│   │           │          
│   │           ├───DependencyInjection   
│   │           │       README.po   
│   │           │          
│   │           ├───Facade   
│   │           │       README.po   
│   │           │          
│   │           ├───FluentInterface   
│   │           │       README.po   
│   │           │          
│   │           ├───Flyweight   
│   │           │       README.po   
│   │           │          
│   │           ├───Proxy   
│   │           │       README.po   
│   │           │          
│   │           └───Registry   
│   │                   README.po   
│   │                      
│   ├───es_MX   
│   │   └───LC_MESSAGES   
│   │       │   README.po   
│   │       │      
│   │       ├───Behavioral   
│   │       │   │   README.po   
│   │       │   │      
│   │       │   ├───ChainOfResponsibilities   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Command   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Iterator   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Mediator   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Memento   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───NullObject   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Observer   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Specification   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───State   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Strategy   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───TemplateMethod   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   └───Visitor   
│   │       │           README.po   
│   │       │              
│   │       ├───Creational   
│   │       │   │   README.po   
│   │       │   │      
│   │       │   ├───AbstractFactory   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Builder   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───FactoryMethod   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Multiton   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Pool   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Prototype   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───SimpleFactory   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Singleton   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   └───StaticFactory   
│   │       │           README.po   
│   │       │              
│   │       ├───More   
│   │       │   │   README.po   
│   │       │   │      
│   │       │   ├───Delegation   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───EAV   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Repository   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   └───ServiceLocator   
│   │       │           README.po   
│   │       │              
│   │       └───Structural   
│   │           │   README.po   
│   │           │      
│   │           ├───Adapter   
│   │           │       README.po   
│   │           │          
│   │           ├───Bridge   
│   │           │       README.po   
│   │           │          
│   │           ├───Composite   
│   │           │       README.po   
│   │           │          
│   │           ├───DataMapper   
│   │           │       README.po   
│   │           │          
│   │           ├───Decorator   
│   │           │       README.po   
│   │           │          
│   │           ├───DependencyInjection   
│   │           │       README.po   
│   │           │          
│   │           ├───Facade   
│   │           │       README.po   
│   │           │          
│   │           ├───FluentInterface   
│   │           │       README.po   
│   │           │          
│   │           ├───Flyweight   
│   │           │       README.po   
│   │           │          
│   │           ├───Proxy   
│   │           │       README.po   
│   │           │          
│   │           └───Registry   
│   │                   README.po   
│   │                      
│   ├───pt_BR   
│   │   └───LC_MESSAGES   
│   │       │   README.po   
│   │       │      
│   │       ├───Behavioral   
│   │       │   │   README.po   
│   │       │   │      
│   │       │   ├───ChainOfResponsibilities   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Command   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Iterator   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Mediator   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Memento   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───NullObject   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Observer   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Specification   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───State   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Strategy   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───TemplateMethod   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   └───Visitor   
│   │       │           README.po   
│   │       │              
│   │       ├───Creational   
│   │       │   │   README.po   
│   │       │   │      
│   │       │   ├───AbstractFactory   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Builder   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───FactoryMethod   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Multiton   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Pool   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Prototype   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───SimpleFactory   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Singleton   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   └───StaticFactory   
│   │       │           README.po   
│   │       │              
│   │       ├───More   
│   │       │   │   README.po   
│   │       │   │      
│   │       │   ├───Delegation   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───EAV   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Repository   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   └───ServiceLocator   
│   │       │           README.po   
│   │       │              
│   │       └───Structural   
│   │           │   README.po   
│   │           │      
│   │           ├───Adapter   
│   │           │       README.po   
│   │           │          
│   │           ├───Bridge   
│   │           │       README.po   
│   │           │          
│   │           ├───Composite   
│   │           │       README.po   
│   │           │          
│   │           ├───DataMapper   
│   │           │       README.po   
│   │           │          
│   │           ├───Decorator   
│   │           │       README.po   
│   │           │          
│   │           ├───DependencyInjection   
│   │           │       README.po   
│   │           │          
│   │           ├───Facade   
│   │           │       README.po   
│   │           │          
│   │           ├───FluentInterface   
│   │           │       README.po   
│   │           │          
│   │           ├───Flyweight   
│   │           │       README.po   
│   │           │          
│   │           ├───Proxy   
│   │           │       README.po   
│   │           │          
│   │           └───Registry   
│   │                   README.po   
│   │                      
│   ├───ru   
│   │   └───LC_MESSAGES   
│   │       │   README.po   
│   │       │      
│   │       ├───Behavioral   
│   │       │   │   README.po   
│   │       │   │      
│   │       │   ├───ChainOfResponsibilities   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Command   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Iterator   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Mediator   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Memento   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───NullObject   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Observer   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Specification   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───State   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Strategy   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───TemplateMethod   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   └───Visitor   
│   │       │           README.po   
│   │       │              
│   │       ├───Creational   
│   │       │   │   README.po   
│   │       │   │      
│   │       │   ├───AbstractFactory   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Builder   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───FactoryMethod   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Multiton   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Pool   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Prototype   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───SimpleFactory   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Singleton   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   └───StaticFactory   
│   │       │           README.po   
│   │       │              
│   │       ├───More   
│   │       │   │   README.po   
│   │       │   │      
│   │       │   ├───Delegation   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───EAV   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   ├───Repository   
│   │       │   │       README.po   
│   │       │   │          
│   │       │   └───ServiceLocator   
│   │       │           README.po   
│   │       │              
│   │       └───Structural   
│   │           │   README.po   
│   │           │      
│   │           ├───Adapter   
│   │           │       README.po   
│   │           │          
│   │           ├───Bridge   
│   │           │       README.po   
│   │           │          
│   │           ├───Composite   
│   │           │       README.po   
│   │           │          
│   │           ├───DataMapper   
│   │           │       README.po   
│   │           │          
│   │           ├───Decorator   
│   │           │       README.po   
│   │           │          
│   │           ├───DependencyInjection   
│   │           │       README.po   
│   │           │          
│   │           ├───Facade   
│   │           │       README.po   
│   │           │          
│   │           ├───FluentInterface   
│   │           │       README.po   
│   │           │          
│   │           ├───Flyweight   
│   │           │       README.po   
│   │           │          
│   │           ├───Proxy   
│   │           │       README.po   
│   │           │          
│   │           └───Registry   
│   │                   README.po   
│   │                      
│   ├───template   
│   │   └───LC_MESSAGES   
│   │       │   README.pot   
│   │       │      
│   │       ├───Behavioral   
│   │       │   │   README.pot   
│   │       │   │      
│   │       │   ├───ChainOfResponsibilities   
│   │       │   │       README.pot   
│   │       │   │          
│   │       │   ├───Command   
│   │       │   │       README.pot   
│   │       │   │          
│   │       │   ├───Iterator   
│   │       │   │       README.pot   
│   │       │   │          
│   │       │   ├───Mediator   
│   │       │   │       README.pot   
│   │       │   │          
│   │       │   ├───Memento   
│   │       │   │       README.pot   
│   │       │   │          
│   │       │   ├───NullObject   
│   │       │   │       README.pot   
│   │       │   │          
│   │       │   ├───Observer   
│   │       │   │       README.pot   
│   │       │   │          
│   │       │   ├───Specification   
│   │       │   │       README.pot   
│   │       │   │          
│   │       │   ├───State   
│   │       │   │       README.pot   
│   │       │   │          
│   │       │   ├───Strategy   
│   │       │   │       README.pot   
│   │       │   │          
│   │       │   ├───TemplateMethod   
│   │       │   │       README.pot   
│   │       │   │          
│   │       │   └───Visitor   
│   │       │           README.pot   
│   │       │              
│   │       ├───Creational   
│   │       │   │   README.pot   
│   │       │   │      
│   │       │   ├───AbstractFactory   
│   │       │   │       README.pot   
│   │       │   │          
│   │       │   ├───Builder   
│   │       │   │       README.pot   
│   │       │   │          
│   │       │   ├───FactoryMethod   
│   │       │   │       README.pot   
│   │       │   │          
│   │       │   ├───Multiton   
│   │       │   │       README.pot   
│   │       │   │          
│   │       │   ├───Pool   
│   │       │   │       README.pot   
│   │       │   │          
│   │       │   ├───Prototype   
│   │       │   │       README.pot   
│   │       │   │          
│   │       │   ├───SimpleFactory   
│   │       │   │       README.pot   
│   │       │   │          
│   │       │   ├───Singleton   
│   │       │   │       README.pot   
│   │       │   │          
│   │       │   └───StaticFactory   
│   │       │           README.pot   
│   │       │              
│   │       ├───More   
│   │       │   │   README.pot   
│   │       │   │      
│   │       │   ├───Delegation   
│   │       │   │       README.pot   
│   │       │   │          
│   │       │   ├───EAV   
│   │       │   │       README.pot   
│   │       │   │          
│   │       │   ├───Repository   
│   │       │   │       README.pot   
│   │       │   │          
│   │       │   └───ServiceLocator   
│   │       │           README.pot   
│   │       │              
│   │       └───Structural   
│   │           │   README.pot   
│   │           │      
│   │           ├───Adapter   
│   │           │       README.pot   
│   │           │          
│   │           ├───Bridge   
│   │           │       README.pot   
│   │           │          
│   │           ├───Composite   
│   │           │       README.pot   
│   │           │          
│   │           ├───DataMapper   
│   │           │       README.pot   
│   │           │          
│   │           ├───Decorator   
│   │           │       README.pot   
│   │           │          
│   │           ├───DependencyInjection   
│   │           │       README.pot   
│   │           │          
│   │           ├───Facade   
│   │           │       README.pot   
│   │           │          
│   │           ├───FluentInterface   
│   │           │       README.pot   
│   │           │          
│   │           ├───Flyweight   
│   │           │       README.pot   
│   │           │          
│   │           ├───Proxy   
│   │           │       README.pot   
│   │           │          
│   │           └───Registry   
│   │                   README.pot   
│   │                      
│   └───zh_CN   
│       └───LC_MESSAGES   
│           │   README.po   
│           │      
│           ├───Behavioral   
│           │   │   README.po   
│           │   │      
│           │   ├───ChainOfResponsibilities   
│           │   │       README.po   
│           │   │          
│           │   ├───Command   
│           │   │       README.po   
│           │   │          
│           │   ├───Iterator   
│           │   │       README.po   
│           │   │          
│           │   ├───Mediator   
│           │   │       README.po   
│           │   │          
│           │   ├───Memento   
│           │   │       README.po   
│           │   │          
│           │   ├───NullObject   
│           │   │       README.po   
│           │   │          
│           │   ├───Observer   
│           │   │       README.po   
│           │   │          
│           │   ├───Specification   
│           │   │       README.po   
│           │   │          
│           │   ├───State   
│           │   │       README.po   
│           │   │          
│           │   ├───Strategy   
│           │   │       README.po   
│           │   │          
│           │   ├───TemplateMethod   
│           │   │       README.po   
│           │   │          
│           │   └───Visitor   
│           │           README.po   
│           │              
│           ├───Creational   
│           │   │   README.po   
│           │   │      
│           │   ├───AbstractFactory   
│           │   │       README.po   
│           │   │          
│           │   ├───Builder   
│           │   │       README.po   
│           │   │          
│           │   ├───FactoryMethod   
│           │   │       README.po   
│           │   │          
│           │   ├───Multiton   
│           │   │       README.po   
│           │   │          
│           │   ├───Pool   
│           │   │       README.po   
│           │   │          
│           │   ├───Prototype   
│           │   │       README.po   
│           │   │          
│           │   ├───SimpleFactory   
│           │   │       README.po   
│           │   │          
│           │   ├───Singleton   
│           │   │       README.po   
│           │   │          
│           │   └───StaticFactory   
│           │           README.po   
│           │              
│           ├───More   
│           │   │   README.po   
│           │   │      
│           │   ├───Delegation   
│           │   │       README.po   
│           │   │          
│           │   ├───EAV   
│           │   │       README.po   
│           │   │          
│           │   ├───Repository   
│           │   │       README.po   
│           │   │          
│           │   └───ServiceLocator   
│           │           README.po   
│           │              
│           └───Structural   
│               │   README.po   
│               │      
│               ├───Adapter   
│               │       README.po   
│               │          
│               ├───Bridge   
│               │       README.po   
│               │          
│               ├───Composite   
│               │       README.po   
│               │          
│               ├───DataMapper   
│               │       README.po   
│               │          
│               ├───Decorator   
│               │       README.po   
│               │          
│               ├───DependencyInjection   
│               │       README.po   
│               │          
│               ├───Facade   
│               │       README.po   
│               │          
│               ├───FluentInterface   
│               │       README.po   
│               │          
│               ├───Flyweight   
│               │       README.po   
│               │          
│               ├───Proxy   
│               │       README.po   
│               │          
│               └───Registry   
│                       README.po   
│                          
├───More   
│   │   README.md   
│   │   README.rst   
│   │      
│   ├───Delegation   
│   │   │   JuniorDeveloper.php   
│   │   │   README.rst   
│   │   │   TeamLead.php   
│   │   │      
│   │   ├───Tests   
│   │   │       DelegationTest.php   
│   │   │          
│   │   └───uml   
│   │           Delegation.uml   
│   │           uml.png   
│   │           uml.svg   
│   │              
│   ├───EAV   
│   │   │   Attribute.php   
│   │   │   Entity.php   
│   │   │   README.rst   
│   │   │   Value.php   
│   │   │      
│   │   ├───Tests   
│   │   │       EAVTest.php   
│   │   │          
│   │   └───uml   
│   │           EAV.uml   
│   │           uml.png   
│   │           uml.svg   
│   │              
│   ├───Repository   
│   │   │   MemoryStorage.php   
│   │   │   Post.php   
│   │   │   PostRepository.php   
│   │   │   README.rst   
│   │   │      
│   │   ├───Tests   
│   │   │       RepositoryTest.php   
│   │   │          
│   │   └───uml   
│   │           Repository.uml   
│   │           uml.png   
│   │           uml.svg   
│   │              
│   └───ServiceLocator   
│       │   LogService.php   
│       │   README.rst   
│       │   ServiceLocator.php   
│       │      
│       ├───Tests   
│       │       ServiceLocatorTest.php   
│       │          
│       └───uml   
│               ServiceLocator.uml   
│               uml.png   
│               uml.svg   
│                  
└───Structural   
    │   README.md   
    │   README.rst   
    │      
    ├───Adapter   
    │   │   Book.php   
    │   │   BookInterface.php   
    │   │   EBookAdapter.php   
    │   │   EBookInterface.php   
    │   │   Kindle.php   
    │   │   README.rst   
    │   │      
    │   ├───Tests   
    │   │       AdapterTest.php   
    │   │          
    │   └───uml   
    │           Adapter.uml   
    │           uml.png   
    │           uml.svg   
    │              
    ├───Bridge   
    │   │   FormatterInterface.php   
    │   │   HelloWorldService.php   
    │   │   HtmlFormatter.php   
    │   │   PlainTextFormatter.php   
    │   │   README.rst   
    │   │   Service.php   
    │   │      
    │   ├───Tests   
    │   │       BridgeTest.php   
    │   │          
    │   └───uml   
    │           Bridge.uml   
    │           uml.png   
    │           uml.svg   
    │              
    ├───Composite   
    │   │   Form.php   
    │   │   InputElement.php   
    │   │   README.rst   
    │   │   RenderableInterface.php   
    │   │   TextElement.php   
    │   │      
    │   ├───Tests   
    │   │       CompositeTest.php   
    │   │          
    │   └───uml   
    │           Composite.uml   
    │           uml.png   
    │           uml.svg   
    │           uml.txt   
    │              
    ├───DataMapper   
    │   │   README.rst   
    │   │   StorageAdapter.php   
    │   │   User.php   
    │   │   UserMapper.php   
    │   │      
    │   ├───Tests   
    │   │       DataMapperTest.php   
    │   │          
    │   └───uml   
    │           DataMapper.uml   
    │           uml.png   
    │           uml.svg   
    │              
    ├───Decorator   
    │   │   JsonRenderer.php   
    │   │   README.rst   
    │   │   RenderableInterface.php   
    │   │   RendererDecorator.php   
    │   │   Webservice.php   
    │   │   XmlRenderer.php   
    │   │      
    │   ├───Tests   
    │   │       DecoratorTest.php   
    │   │          
    │   └───uml   
    │           Decorator.uml   
    │           uml.png   
    │           uml.svg   
    │              
    ├───DependencyInjection   
    │   │   DatabaseConfiguration.php   
    │   │   DatabaseConnection.php   
    │   │   README.rst   
    │   │      
    │   ├───Tests   
    │   │       DependencyInjectionTest.php   
    │   │          
    │   └───uml   
    │           DependencyInjection.uml   
    │           uml.png   
    │           uml.svg   
    │              
    ├───Facade   
    │   │   BiosInterface.php   
    │   │   Facade.php   
    │   │   OsInterface.php   
    │   │   README.rst   
    │   │      
    │   ├───Tests   
    │   │       FacadeTest.php   
    │   │          
    │   └───uml   
    │           Facade.uml   
    │           uml.png   
    │           uml.svg   
    │              
    ├───FluentInterface   
    │   │   README.rst   
    │   │   Sql.php   
    │   │      
    │   ├───Tests   
    │   │       FluentInterfaceTest.php   
    │   │          
    │   └───uml   
    │           FluentInterface.uml   
    │           uml.png   
    │           uml.svg   
    │              
    ├───Flyweight   
    │   │   CharacterFlyweight.php   
    │   │   FlyweightFactory.php   
    │   │   FlyweightInterface.php   
    │   │   README.rst   
    │   │      
    │   ├───Tests   
    │   │       FlyweightTest.php   
    │   │          
    │   └───uml   
    │           Flyweight.uml   
    │           uml.png   
    │           uml.svg   
    │              
    ├───Proxy   
    │   │   README.rst   
    │   │   Record.php   
    │   │   RecordProxy.php   
    │   │      
    │   ├───Tests   
    │   │       ProxyTest.php   
    │   │          
    │   └───uml   
    │           Proxy.uml   
    │           uml.png   
    │           uml.svg   
    │              
    └───Registry   
        │   README.rst   
        │   Registry.php   
        │      
        ├───Tests   
        │       RegistryTest.php   
        │          
        └───uml   
                Registry.uml   
                uml.png   
                uml.svg




[![Build Status](https://travis-ci.org/domnikl/DesignPatternsPHP.svg?branch=master)](https://travis-ci.org/domnikl/DesignPatternsPHP)

[Read the Docs of DesignPatternsPHP](http://designpatternsphp.readthedocs.org)
or [Download as PDF/Epub](https://readthedocs.org/projects/designpatternsphp/downloads/)

This is a collection of known design patterns and some sample code how to implement them in PHP. Every pattern has a small list of examples (most of them from Zend Framework, Symfony2 or Doctrine2 as I'm most familiar with this software).

I think the problem with patterns is that often people do know them but don't know when to apply which.

## Installation
You should look at and run the tests to see what happens in the example.
To do this, you should install dependencies with `Composer` first:

### [optional] Using a Virtual Machine (VM)

If you wish to use a ready made VM environment, you can easily create one with Vagrant and Ansible.

```bash
$ vagrant up
```

Then `vagrant ssh` and `cd /vagrant`

More information on [vagrant](https://www.vagrantup.com)

### Install dependencies

```bash
$ composer install
```

Read more about how to install and use `Composer` on your local machine [here](https://getcomposer.org/doc/00-intro.md#installation-linux-unix-osx).

### Running test suite

```bash
$ ./vendor/bin/phpunit
```

## Patterns

The patterns can be structured in roughly three different categories. Please click on the [:notebook:](http://en.wikipedia.org/wiki/Software_design_pattern) for a full explanation of the pattern on Wikipedia.

### [Creational](Creational)

* [AbstractFactory](Creational/AbstractFactory) [:notebook:](http://en.wikipedia.org/wiki/Abstract_factory_pattern)
* [Builder](Creational/Builder) [:notebook:](http://en.wikipedia.org/wiki/Builder_pattern)
* [FactoryMethod](Creational/FactoryMethod) [:notebook:](http://en.wikipedia.org/wiki/Factory_method_pattern)
* [Multiton](Creational/Multiton) (is considered an anti-pattern! :no_entry:)
* [Pool](Creational/Pool) [:notebook:](http://en.wikipedia.org/wiki/Object_pool_pattern)
* [Prototype](Creational/Prototype) [:notebook:](http://en.wikipedia.org/wiki/Prototype_pattern)
* [SimpleFactory](Creational/SimpleFactory)
* [Singleton](Creational/Singleton) [:notebook:](http://en.wikipedia.org/wiki/Singleton_pattern) (is considered an anti-pattern! :no_entry:)
* [StaticFactory](Creational/StaticFactory)

### [Structural](Structural)

* [Adapter](Structural/Adapter) [:notebook:](http://en.wikipedia.org/wiki/Adapter_pattern)
* [Bridge](Structural/Bridge) [:notebook:](http://en.wikipedia.org/wiki/Bridge_pattern)
* [Composite](Structural/Composite) [:notebook:](http://en.wikipedia.org/wiki/Composite_pattern)
* [DataMapper](Structural/DataMapper) [:notebook:](http://en.wikipedia.org/wiki/Data_mapper_pattern)
* [Decorator](Structural/Decorator) [:notebook:](http://en.wikipedia.org/wiki/Decorator_pattern)
* [DependencyInjection](Structural/DependencyInjection) [:notebook:](http://en.wikipedia.org/wiki/Dependency_injection)
* [Facade](Structural/Facade) [:notebook:](http://en.wikipedia.org/wiki/Facade_pattern)
* [FluentInterface](Structural/FluentInterface) [:notebook:](http://en.wikipedia.org/wiki/Fluent_interface)
* [Flyweight](Structural/Flyweight) [:notebook:](https://en.wikipedia.org/wiki/Flyweight_pattern)
* [Proxy](Structural/Proxy) [:notebook:](http://en.wikipedia.org/wiki/Proxy_pattern)
* [Registry](Structural/Registry) [:notebook:](http://en.wikipedia.org/wiki/Service_locator_pattern)

### [Behavioral](Behavioral)

* [ChainOfResponsibilities](Behavioral/ChainOfResponsibilities) [:notebook:](http://en.wikipedia.org/wiki/Chain_of_responsibility_pattern)
* [Command](Behavioral/Command) [:notebook:](http://en.wikipedia.org/wiki/Command_pattern)
* [Iterator](Behavioral/Iterator) [:notebook:](http://en.wikipedia.org/wiki/Iterator_pattern)
* [Mediator](Behavioral/Mediator) [:notebook:](http://en.wikipedia.org/wiki/Mediator_pattern)
* [Memento](Behavioral/Memento) [:notebook:](http://en.wikipedia.org/wiki/Memento_pattern)
* [NullObject](Behavioral/NullObject) [:notebook:](http://en.wikipedia.org/wiki/Null_Object_pattern)
* [Observer](Behavioral/Observer) [:notebook:](http://en.wikipedia.org/wiki/Observer_pattern)
* [Specification](Behavioral/Specification) [:notebook:](http://en.wikipedia.org/wiki/Specification_pattern)
* [State](Behavioral/State) [:notebook:](http://en.wikipedia.org/wiki/State_pattern)
* [Strategy](Behavioral/Strategy) [:notebook:](http://en.wikipedia.org/wiki/Strategy_pattern)
* [TemplateMethod](Behavioral/TemplateMethod) [:notebook:](http://en.wikipedia.org/wiki/Template_method_pattern)
* [Visitor](Behavioral/Visitor) [:notebook:](http://en.wikipedia.org/wiki/Visitor_pattern)

### [More](More)
* [Delegation](More/Delegation) [:notebook:](http://en.wikipedia.org/wiki/Delegation_pattern)
* [ServiceLocator](More/ServiceLocator) [:notebook:](http://en.wikipedia.org/wiki/Service_locator_pattern) (is considered an anti-pattern! :no_entry:)
* [Repository](More/Repository)
* [EAV](More/EAV) [:notebook:](https://en.wikipedia.org/wiki/Entity%E2%80%93attribute%E2%80%93value_model)

## Contribute

If you encounter any bugs or missing translations, please feel free to fork and send a pull request with your changes.
To establish a consistent code quality, please check your code using [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) against [PSR2 standard](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md) using `./vendor/bin/phpcs -p --standard=PSR2 --ignore=vendor .`.

## License

(The MIT License)

Copyright (c) 2011 - 2017 Dominik Liebler and [contributors](https://github.com/domnikl/DesignPatternsPHP/graphs/contributors)

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
