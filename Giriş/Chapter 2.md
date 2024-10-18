## Step 1
1. Scripts klasörü açılır.
2. PlayerController scripti yaratılır. "Naming convention".
3. Script i sürükleyerek Vehicle a component olarak ekliyoruz.
4. (componentler objelere atadığımız özellikler??
   1- transform
   2- mesh renderer: araç texture unu görmemizi sağlar
   3- mesh collider )

## Step 2
1. Scripte tıklayarak visual studio açılır.
2. Theme
3. Class ve inheritance
4. fonksiyonlar
5. Update kısmını comment olarak //Move vehicle forward gibi bi sey yazılır
6. 

## Step 3
1. C# kullanarak kod yazmak.
2. Unity de araç ileri sürüklenir ve hangi transform position takip edilir Z oldugu anlaşılır.
3. `transform.Translate(0,0,1);` yazılır.
4. CTRL + S ile save.
5. Araç incelenir.

## Step 4
1. help
2. `transform.Translate(Vector3.forward);` okunabilirlik için önemli.
3. 

## Step 5
1. per frame kavramı cihazın gücüne göre değişiklik göstermektedir.
2. `transform.Translate(Vector3.forward * Time.deltaTime);` : zaman farkını kullanarak normal 1 saniyeye fixler. Saniyede +1 Z gidilir.
3. `transform.Translate(Vector3.forward * Time.deltaTime * 20);` : hızlandır.
4. 1Z * time * 20 = 20 metre/saniye
5. 


## Step 6
1. Fizik simule edebilmek icin objelerimize RigidBody componenti ekliyoruz.
2. Mass vb. bahsedilir.
3. Mesh collider dan bahsedilir. Çarpışılabilir kılar.
4. Play e basılıp, durum izlenir.
5. Mesh collider kapatılıp durum izlenir, ne işe yaradığı anlaşılır.
6. Araba = 1000, obstacle = 20 yapılır.
7. 

## Step 7
1. Obstacle en aşağı sıraya taşınır.
2. CTRL + D ile duplike edilir.
3. 7 tane falan sıra halinde dizilir. CTRL ile ve SHIFT ile seçmeler gösterilir.


