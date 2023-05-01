# NewsApp

The objective is to develop a mobile application that retrieves the most recent news feed from the newsapi.org API. Upon login, users can view news based on their preferred categories and location. The application is being built using the Flutter framework, which manages the View and Control aspects, adhering to the MVC architecture. User information is kept on Firebase.

<br>

### Team Members: 
Krishna Sandeep Reddy Chittiepu & Dheeraj Reddy Inugala

<br>

### Requirements:
1. Flutter Version: 3.3.10
2. Dart Version: >=2.18.0 <3.0.0
3. X Code
4. Visual Studio Code

Run the <code>flutter doctor</code> command to check whether all the requirements are satisfied or not.

<br>

### Steps to run the project:

1. Clone and project and cd to the newsapp directory. 

2. Install Mason (Mason is a command-line tool that allows you to generate a customized codebase based on your specifications.) and Dart CLI.

3. Activate Mason and Dart CLI's using the following commands 
* <code>pub global activate mason_cli</code>
* <code>dart pub global activate dart_frog_cli</code>

4. cd to the <code>api</code> directory and run the <code>dart_frog dev</code> command.

5. Open the IOS simulator using the <code>open -a simulator</code> command.

6. Finally, run the flutter app using 
   <br><code>flutter run \ \
  --flavor development \ \
  --target lib/main/main_development.dart</code>


