كود بدائي تعريف لبعض الكتببلغة جافا

//خصائص الكتاب //
class Book{
    String title;// عنوان الكتاب //
    String author;//اسم الكاتب //
    int year;//سنه النشر //
    // 
    Book(){
        this.title="فن اللامبالا";
        this.author="مارك مانسون";
        this.year=2016;
    }
    Book(String title){
        this.title=title;
        this.author=" جم كولينز";
        this.year=2001;
    }
     Book(String title,String author){
        this.title= title;
        this.author= author;
        this.year=1997;
    }
 void PrintOfInfe(){
     System.out.println("title :"+(title)+"author :"+(author)+"year"+year);}
 }
public class Main {
    public static void main(String[] args) {
Book b1=new Book();
Book b2=new Book("من جيد الى عظيم");
Book b3=new Book("Rich Dad Poor Dad"," روبرت كيوساكي");

b1.PrintOfInfe();
b2.PrintOfInfe();
b3.PrintOfInfe();

        }
}
