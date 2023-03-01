# Code-for-Class-file-Animal.java-

public abstract class Animal {

    public String picture;
    protected String name;
    protected int age;


    public Animal (String picture, String name, int age) {
        this.picture = picture;
        this.name = name;
        this.age = age;
  }
    public int getAge() {
        return age;
    }

    public void birthday() {
        age++;
    }
    public void madeSound() {
        System.out.println(this.name + " made a sound!");
    }
}
