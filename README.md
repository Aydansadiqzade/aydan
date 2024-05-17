# include <stdio.h>

int main() {
    int n, toplam = 0, sayi;

    printf("Kaç adet sayı gireceksiniz: ");
    scanf("%d", &n);

    // Kullanıcıdan n adet sayı alınıyor ve toplanıyor
    printf("Lütfen sayıları giriniz:\n");
    for (int i = 0; i < n; i++) {
        scanf("%d", &sayi);
        toplam += sayi;
    }

    // Toplam ekrana yazdırılıyor
    printf("Girdiğiniz sayıların toplamı: %d\n", toplam);

    return 0;
}
