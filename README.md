# Tugas III Mobile Programming
- Silahkan download dan install sqlite di laptop masing-masing
- Buat 1 database dengan format “nim_nama.db”
- Buat 2 buah tabel:
  - Tbl_product berisi:
      ```json
        {
          "id" : "int",
          "sku" : "text",
          "nama_produk" : "text",
          "kategori" : "text"
      }
    ```
  - Tbl_customer berisi
      ```json
        {
          "id" : "int",
          "nama_pelanggan" : "text",
          "alamat" : "char",
          "email" : "varchar"
        }
      ```
- Tambahkan 5 data ke masing-masing tabel
- Submit file database yang dibuat ke sistem akademik dengan cara upload terlbih
  dahulu ke repository seperti github, google drive, dsb kemudian submit file yang
  berisi linknya ke sistem akademik atau kirimkan via wagroup untuk linknya

## Tabel Product
```json
{
  "Tbl_product": [
    {
      "id": 1,
      "sku": "JP10001",
      "nama_produk": "Pocky Chocolate",
      "kategori": "Snack"
    },
    {
      "id": 2,
      "sku": "JP10002",
      "nama_produk": "Kit Kat Matcha",
      "kategori": "Snack"
    },
    {
      "id": 3,
      "sku": "JP10003",
      "nama_produk": "Calbee Shrimp Chips",
      "kategori": "Snack"
    },
    {
      "id": 4,
      "sku": "JP10004",
      "nama_produk": "Jagabee Potato Sticks",
      "kategori": "Snack"
    },
    {
      "id": 5,
      "sku": "JP10005",
      "nama_produk": "Hi-Chew Grape",
      "kategori": "Candy"
    },
    {
      "id": 6,
      "sku": "JP10006",
      "nama_produk": "Ramune Soda",
      "kategori": "Minuman"
    },
    {
      "id": 7,
      "sku": "JP10007",
      "nama_produk": "Puccho Cola",
      "kategori": "Candy"
    },
    {
      "id": 8,
      "sku": "JP10008",
      "nama_produk": "Tokyo Banana",
      "kategori": "Snack"
    },
    {
      "id": 9,
      "sku": "JP10009",
      "nama_produk": "Meltykiss Chocolate",
      "kategori": "Snack"
    },
    {
      "id": 10,
      "sku": "JP10010",
      "nama_produk": "UCC Coffee with Milk",
      "kategori": "Minuman"
    }
  ]
}
```

## Tabel Customer
```json
{
  "Tbl_customer": [
    {
      "id": 1,
      "nama_pelanggan": "",
      "alamat": "",
      "email": ""
    },
    {
      "id": 2,
      "nama_pelanggan": "",
      "alamat": "",
      "email": ""
    },
    {
      "id": 3,
      "nama_pelanggan": "",
      "alamat": "",
      "email": ""
    },
    {
      "id": 4,
      "nama_pelanggan": "",
      "alamat": "",
      "email": ""
    },
    {
      "id": 5,
      "nama_pelanggan": "",
      "alamat": "",
      "email": ""
    }
  ]
}
```
