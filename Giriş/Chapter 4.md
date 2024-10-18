## Step 1
1. `public float turnSpeed;` eklenir.
2. `transform.Translate(Vector3.right * Time.deltaTime * turnSpeed);` eklenir.
3.  Inspectordan speed ayarlanır.

## Step 2 INPUT
1. Edit - Project Settings - Input Settings - Axes
2. `public float horizontalInput;` yazılır.
3. `horizontalInput = Input.GetAxis("Horizontal");` yazılır Update içine.
4. `transform.Translate(Vector3.right * Time.deltaTime * turnSpeed * horizontalInput);`  horizontal input ile çarpılır.

## Step 3
1. `public float verticalInput;` tanımlanır.
2. `verticalInput = Input.GetAxis("Vertical");` Update a yazılır.
3. `transform.Translate(Vector3.forward * Time.deltaTime * speed * verticalInput);`  vertical input ile çarpılır.

## Step 4
1. `transform.Rotate();` denenir. Vector3.Up ın Y axis olduğu bilinir.
2. `transform.Rotate(Vector3.Up, Time.deltaTime * turnSpeed * horizontalInput);` yapılır. Hız düzeltilir.

## Step 5
1.  [[Challange]]
