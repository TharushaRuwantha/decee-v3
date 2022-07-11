# Dicee v3 

I clone the decee- fluter project from londonappBrew but it did not work. so i created this repo for who want the updated working version of dicee-fluter project


# You can clone this project and use or create your own updated Dicee project

  # step 1
   create a new flutter project 
  
  # step 2
   copy and past the bellow code in your main.dart file
   
     import 'package:flutter/material.dart';

        void main() {
          return runApp(
            MaterialApp(
              home: Scaffold(
                backgroundColor: Colors.red,
                appBar: AppBar(
                  title: Text('Dicee'),
                  backgroundColor: Colors.red,
                ),
                body: DicePage(),
              ),
            ),
          );
        }

        class DicePage extends StatelessWidget {
          @override
          Widget build(BuildContext context) {
            return Container();
          }
        }
        
        
   # step 3
   update the pugspec.yaml file in your new project 
   
      assets:
    - images/
* be sure about indentation![image](https://user-images.githubusercontent.com/87405522/178193192-996d8c09-6f34-4dab-9796-2f342a59939b.png)

# step 4 
(now you are good to go but is you need app icons the follow the this step)

go inside ios > Runner and  then delete the 'Assets.xcassets' folder in your new flutter project and copy the same folder in old(decee-flutter project) and paste in your new project inside (ios > Runner)

   ![image](https://user-images.githubusercontent.com/87405522/178194965-0c2ea727-260b-4836-98f4-5047818f040a.png)

now go inside the android > app > src > main > res  and then select the bellow folders and delete them and replace *only* the same named folders from the old project ( decee-flutter)

![image](https://user-images.githubusercontent.com/87405522/178194166-7f6902d1-c4c7-45db-8527-98c02c3f2fbf.png)



  
