# scalalab

## Easy and Efficient Matlab-like scientific computing in Scala ##


## Project Summary#

`The ScalaLab project aims to provide an efficient scientific programming environment for the Java Virtual Machine. The scripting language is based on the Scala programming language enhanced with high level scientific operators and with an integrated environment that provides a MATLAB-like working style. Also, all the huge libraries of Java scientific code can be easily accessible (and many times with a more convenient syntax). The main potential of the ScalaLab is numerical code speed and flexibility. The statically typed Scala language can provide speeds of scripting code similar to pure Java. A major design priority of ScalaLab is its user-friendly interface. We like the user to enjoy writing scientific code, and with this objective we design the whole framework.`

`The MATLAB-like mathematical DSL of ScalaLab is termed ScalaSci , and is developed as an internal DSL, by exploiting the superb extensibility of the Scala language.`

`Toolboxes of Java scientific code can be easily installed, using a menu based installation procedure. Also, any .jar packed toolbox, can be directly available by placing it at the defaultToolboxes folder.`

`Many environment configuration options can be easily performed within the graphical user interface. Also,  code completion features and on line help support on the contents of classes, objects, libraries etc., using Java/Scala reflection, can further facilitate the programmer.`

`ScalaLab utilizes also and native C/C++ code for some important numerical operations. Although the speed  of pure Java code is generally adequate, optimized native code can provide further additional improvement. Also, the Java Native Interface (JNI) is utilized to interface with NVIDIA's CUDA technology, that provides dramatic speed improvements for many important tasks.`

## Installation

`ScalaLab is developed with JDK8, so make sure to have JDK8 installed.`

`To install and execute ScalaLab, download the .zip , and unzip it.  `

`The .zip download contains both the sources and all the relevant libraries to build  ScalaLab with sbt.`

`Then execute the appropriate .bat script for Windows or the corresponding .sh script for UNIX users. The script configures the java.library.path and some JVM parameters.`

`To build ScalaLab with SBT:`


`1. Unzip the .zip file`

`2. Type` 

`sbt`

`then at the SBT prompt, type `

`clean`

`and then`

`package`


## ScalaLab Advantages

`The main advantages of ScalaSci that equip it with great potential are:`

`The flexibility and scalability of the wonderful and powerful Scala language, that offer many opportunities to implement convenient high-level scientific operators.`

`The speed of Scala based scripting, that approaches the speed of native and optimized Java code, and thus is close to, or even better from C/C++ based scientific code!`

`The vast Java based scientific libraries with excellent code for many application domains.  These libraries are directly available from ScalaSci with the dynamic loading of the corresponding Java toolboxes.`

`The user friendly MATLAB -like environment of ScalaLab and the high quality scientific plotting support. ScalaLab can directly call and access the results of MATLAB scripts.`

## Contributing in ScalaSci development

`The recent ScalaSci code can be found from the latest ScalaLab sources. The easier and faster way to develop extensions to the ScalaSci classes is from within ScalaLab itself. In that way, new ScalaSci classes can be created without a cumbersome building of the sources. ScalaLab Contributors are welcomed: If you develop interesting extensions, please contact me to include them within the ScalaLab sources and have your name in the ScalaLab contributors list`
 
