# <span style="color:#5207a6">tienda-db</span>


## <style="color:#a5140b>"POJOs</span>

<b>Product</b>
- id: int
- name: String
- price: double


<b>Tag</b>
- id: int
- name: String


<b>ProductTag</b>
- productId: int
- tagId: int


<b>Customer</b>
- nif: String
- name: String
- surname: String


<b>Order</b>
- id: int
- customerNif: String
- date: Date
- price: double


<b>OrderItem</b>
- orderId: int
- productId: int
- amount: int




## Componentes

<b>ProductDAO</b>
- Insertar, listar, eliminar


<b>TagDAO</b>
- Insertar, listar, eliminar


<b>CustomerDAO</b>
- Insertar, listar, eliminar


<b>OrderDAO</b>
- Insertar, listar, eliminar


<b>OrderItemDAO</b>
- Insertar, listar, eliminar



## TiendaApp


Debe implementar un bucle con las siguientes opciones:

- Listar productos

- Insertar producto

- Ver etiquetas

- Insertar etiqueta

- Asociar etiqueta a producto

- Listar clientes

- Insertar cliente

- Ver pedidos de cliente

- Ver detalles de pedido

- Añadir nuevo pedido
