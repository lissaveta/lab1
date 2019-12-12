package lab1;

public class ball {
    private String color;
    private String size;

    public  ball(String color, String size){
        this.color = color;
        this.size = size;
    }

    public void setColor(String color){
        this.color = color;
    }

    public String getColor(){
        return color;
    }

    public void setSize(String size){
        this.size = size;
    }

    public String getSize(){
        return size;
    }

    public String toString(){
        return ("Size : " + size +"\nColor : " + this.color );
    }
}
class TestBall {
    public static void main(String[] arg){
        ball b1 = new ball("Red","L");
        System.out.println(b1.toString());
    }
}
