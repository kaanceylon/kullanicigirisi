# kullanicigirisi
kullanıcı girişi programı

    import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        String userName, password,answer, newPassword;

        Scanner input =  new Scanner(System.in);
        System.out.print("Kullanıcı adınızı giriniz :");
        userName = input.nextLine();

        System.out.print("Kullanıcı şifrenizi giriniz :");
        password = input.nextLine();

        if (userName.equals("Kaan") && password.equals("kaan123")){
            System.out.print("Giriş yaptınız :");
        } else if (!userName.equals("Kaan") && password.equals("kaan123")) {
            System.out.print("Kullanıcı adınız yanlış :");
        } else if (userName.equals("Kaan") && !password.equals("kaan123")) {
            System.out.print("Şifreniz yanlış :");
            System.out.print("Yeni bir şifre oluşturmak ister misiniz --> 'yes/no' ? :");
            Scanner sifre = new Scanner(System.in);
            answer = sifre.nextLine();
            if (answer.equals("yes")){
            System.out.println("Yeni şifrenizi girin : ");
            Scanner change = new Scanner(System.in);
            newPassword = input.nextLine();
            if (newPassword.equals("kaan123")){
                System.out.print("Yeni şifreniz eski şifrenizle aynı olamaz :");
            }else {
                System.out.print("Yeni şifrenizi giriniz :");

                
            }

        }
        {

        }









        }

        } }






