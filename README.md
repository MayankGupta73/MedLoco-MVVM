# MedLoco-MVVM
Implementation of the MedLoco app using the MVVM architecture

This version uses the Model-View-ViewModel Architecture to implement the MedLoco Application.
I have used the Android LiveData and ViewModel classes instead of any external libraries like RxJava.

The architecture has the following components:

- <h3>Model</h3>
 This contains the logic of the app including fetching of data and other back-end.
 
 - <h3>View</h3>
 This comprises the UI of the app including all activities and fragments. They implement observer and basically wait for changes to the ViewModel.
 
 - <h3>ViewModels</h3>
 The ViewModels are the mediator between UI and data repository. They implement the observable class and inform the View of any changes.
 The app has three ViewModels:<br>
  <pre>MapViewModel   ListViewModel   DetailViewModel</pre>
 
 
