## Step 1
1. Hardcoded speed i public bir float a çeviriyoruz.
2. `float speed = 5.0;`
3. `float speed = 5.0f;`
4. 20 yi speed ile değiştir.
6. `public float speed = 5.0f;`
7. Inspectordan speedi değiştir.
8. 

## Step 2
1. FollowPlayer scripti oluşturulur.
2. Main Cameraya eklenir.
3. `public GameObject player;` eklenir
4. Vehicle oraya sürüklenir.
5. Update kısmına: `transform.position = player.transform.position; yazılır.
6. Kameranın transformuna bakılıp kopya çekilir.
7. `(0, 5, -7)` eklenmeye çalışılr.
8. `transform.position = player.transform.position + new Vector3(0, 5, -7);` yazılır bir offset eklenir.
9. 

## Step 3
1. `private Vector3 offset = new Vector3(0, 5, -7);` olarak temize çekilir.
2. Update içine offset yazılır.

## Step 4
1. Kamera titremesini geçirmek için LateUpdate() kullanılır. FollowPlayer scriptinde.

## Step 5
1. Edit - preferences - colors - playmode color
