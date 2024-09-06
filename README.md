# Discussion1
public class Main {
    
        public static void main(string[]args) {
            //Creating objects to the Animal class
            Animal animal1 = new Animal("lion", 7);
            Animal animal2 = new Animal("dog", 9);
            Animal animal3 = new Animal("cat", 3);
    
            //Showing information about the objects
            System.out.println("Animal 1" + animal1.getName() + ", Age: " + animal1.getAge());
            System.out.println("Animal 2" + animal2.getName() + ", Age: " + animal2.getAge());
            System.out.println("Animal 3" + animal3.getName() + ", Age: " + animal3.getAge());
            
        }
    
        class Animal {
            private String name;
            private int age;

            public Animal (String name, int age) {
                this.name = name;
                this.age = age;
            }

            //Getting the class name
            public String getName() {
                return name;
            }

            //Getting the class age
            public int getAge(){
                return age;
            }

            //Setting age
            public void setAge(int age){
                this.age = age;
            }
        }

}
