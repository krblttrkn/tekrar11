# HAVA SICAKLIĞINA GÖRE ETKİNLİK ÖNERME
## Koşullar :
* Sıcaklık 5'ten küçük ise 'Kayak' yapmayı öner.
* Sıcaklık 5 ve 15 arasında ise 'Sinema' etkinliğini öner.
* Sıcaklık 10 ve 25 arasında ise 'Piknik' etkinliğini öner.
* Sıcaklık 25'ten büyük ise 'Yüzme Havuzu' etkinliğini öner.

# Ödev
* Aynı örnek üzerinden if koşulları başka hangi şekilde oluşturulabilirdi Farklı çözüm yolları bulunuz.(Çok uğraştım ama başka nasıl olabilir bulamadım. Bu ödev burada kalsın bulduğum zaman tekrardan geriye dönüp yapacağım.)

```
import java.util.Scanner;

public class HavaSicakligi {
    public static void main(String[] args){
        int heat;
        Scanner input = new Scanner(System.in);

        System.out.print("Sıcaklığı Giriniz :");
        heat=input.nextInt();

        if(heat<5){
            System.out.print("Kayak Yapınız");
        }else if(heat<25){
            if(heat<15){
                System.out.print("Sinemaya Gidebilirsiniz");
            }
            if(heat>10){
                System.out.print("Pikniğe Gidebilirsin");
            }
        }else{
            System.out.print("Yüzmeye Gidebilirsin");
        }
    }
}
```
# Patika Profilim
***
<a href="https://academy.patika.dev/profile">Patika Profilim</a>