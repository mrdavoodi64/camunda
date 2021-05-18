# CallActivity

In this example we show how to use CallActivity in a bpmn model. We have a MainProcess and a ChildProcess. 
![image](https://user-images.githubusercontent.com/37771899/118640256-03df5700-b7ee-11eb-8147-2a1b7700cb97.png)

1. we want to call a bpmn model so we choose BPMN as callactivity type.
2. we fill called element field with the process id of the child process.
3. set binding as lastest means we want to use the last deployment of the child process.

![image](https://user-images.githubusercontent.com/37771899/118640918-c62efe00-b7ee-11eb-9bd2-7158ba4e6a11.png)

In the in mapping box, we declare which variables from the MainProcess(source) should be passed to the ChildProcess(target).

In the out mapping box, we declare which variables from the ChildProcess(source) should be passed to the MainProcess(target).

Check the local option, means that we only want to pass the variables that are defined in the Input/Output tab.

Deploy, run and see the result in action.

