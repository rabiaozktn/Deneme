---
author: Rabia Özaktan
lang: tr
---

# Whatsgoo

### Search product

| Request Type | Route                                                    | Query Params |
| ------------ | -------------------------------------------------------- | ------------ |
| `GET`        | whatsgoo/tenants/acme/taxonomies/:id/taxons/:id/products | q=product    |

#### Response | `200`

```json
{
  "products": [
    {
      "id": 422,
      "name": "Temporary Product for Fuudy",
      "display_name": "Temporary Product for Fuudy",
      "description": null,
      "status": "available",
      "warranty_period": null,
      "warranty_type": null,
      "master": true,
      "extras_exists": false,
      "selectable_extras_exists": false,
      "created_at": "2020-07-19T14:33:51.601+03:00",
      "updated_at": "2020-07-19T14:33:51.648+03:00",
      "taxons": [
        {
          "id": 78,
          "name": "test",
          "description": "test",
          "visible": true,
          "logo": "",
          "position": 3,
          "full_path": "taxonomy 2 -> test",
          "created_at": "2020-07-18T01:12:10.512+03:00",
          "updated_at": "2020-07-18T01:12:10.512+03:00"
        }
      ],
      "option_types": [],
      "product_extras": [],
      "display_price": "0.0",
      "type": "simple",
      "currency": {
        "symbol": "₺",
        "disambiguate_symbol": "₺",
        "subunit_symbol": null,
        "iso_code": "TRY",
        "iso_numeric": "949",
        "name": "Turkish Lira",
        "smallest_denomination": 1,
        "subunit_to_unit": 100,
        "decimal_mark": ",",
        "minor_units": 2
      }
    }
  ]
}
```

---

### Get a taxon's products

| Request Type | Route                                                    |
| ------------ | -------------------------------------------------------- |
| `GET`        | whatsgoo/tenants/acme/taxonomies/:id/taxons/:id/products |

#### Response | `200`

```json
{
  "products": [
    {
      "id": 2,
      "name": "Coca-Cola Light 330 ML Kutu, 24 Adet",
      "display_name": "Coca-Cola Light 330 ML Kutu, 24 Adet",
      "description": "<h1><strong><span style=\"font-size:12px;\">İçindekiler</span></strong></h1>\n\n<h1><span style=\"font-size:12px;\">\n<p>*Su, karbondioksit, renklendirici (karamel), asitliği düzenleyiciler (fosforik asit, sitrik asit), doğal aroma vericiler, tatlandırıcılar*(aspartam**, asesulfam-K), koruyucu (sodyum benzoat), kafein (maks. 0.150 g/l). Kafein içerir.</p>\n\n<p>*Tatlandırıcı içerir.</p>\n\n<p>**Fenilalanin kaynağı içerir.</p>\n\n<p>Enerji ve Besin Öğeleri 100 ml</p>\n\n<p>Enerji 0,2 kcal (0,8 kJ)</p>\n\n<p>Yağ 0,0 g</p>\n\n<p>Doymuş Yağ 0,0 g</p>\n\n<p>Karbonhidrat 0,0 g</p>\n\n<p>Şeker 0,0 g</p>\n\n<p>Lif 0,0 g</p>\n\n<p>Protein 0,0 g</p>\n</span>\n\n<p>&nbsp;</p>\n<span style=\"font-size:12px;\">\n<p>Sodyum 0,0 g</p>\n</span></h1>",
      "status": "available",
      "warranty_period": 0,
      "warranty_type": "day",
      "master": true,
      "extras_exists": false,
      "selectable_extras_exists": false,
      "created_at": "2020-06-20T22:04:27.175+03:00",
      "updated_at": "2020-06-21T22:06:50.492+03:00",
      "taxons": [
        {
          "id": 1,
          "name": "Süpermarket",
          "description": null,
          "visible": true,
          "logo": "",
          "position": 0,
          "full_path": "Kategoriler -> Süpermarket",
          "created_at": "2020-06-20T22:04:26.226+03:00",
          "updated_at": "2020-06-20T22:04:26.226+03:00"
        },
        {
          "id": 30,
          "name": "İçeçek",
          "description": "İçecek ürünleri uygun fiyatlarıyla birlikte HepGelsin'de! Hemen 50 TL ve üzeri ücretsiz kargo fırsatıyla Coca-Cola, Fanta, Sprite, Fuse Tea, Cappy keşfedin",
          "visible": true,
          "logo": "",
          "position": 0,
          "full_path": "Kategoriler -> Süpermarket -> İçeçek",
          "created_at": "2020-06-20T22:04:26.717+03:00",
          "updated_at": "2020-06-20T22:04:27.102+03:00"
        },
        {
          "id": 31,
          "name": "Gazlı İçeçek",
          "description": "Coca Cola ve gazoz çeşitleri uygun fiyatlarıyla birlikte HepGelsin'de! Hemen 50 TL ve üzeri ücretsiz kargo fırsatıyla keşfedin!",
          "visible": true,
          "logo": "",
          "position": 0,
          "full_path": "Kategoriler -> Süpermarket -> İçeçek -> Gazlı İçeçek",
          "created_at": "2020-06-20T22:04:26.738+03:00",
          "updated_at": "2020-06-20T22:04:27.111+03:00"
        },
        {
          "id": 25,
          "name": "Coca-Cola Light",
          "description": null,
          "visible": true,
          "logo": "",
          "position": 0,
          "full_path": "Markalar -> Coca-Cola -> Coca-Cola Light",
          "created_at": "2020-06-20T22:04:26.597+03:00",
          "updated_at": "2020-06-20T22:04:27.194+03:00"
        }
      ],
      "option_types": [],
      "product_extras": [],
      "display_price": "64.0",
      "type": "simple",
      "currency": {
        "symbol": "₺",
        "disambiguate_symbol": "₺",
        "subunit_symbol": null,
        "iso_code": "TRY",
        "iso_numeric": "949",
        "name": "Turkish Lira",
        "smallest_denomination": 1,
        "subunit_to_unit": 100,
        "decimal_mark": ",",
        "minor_units": 2
      }
    },
    {
      "id": 3,
      "name": "Coca-Cola Şekersiz 330 ML Kutu, 24 Adet",
      "display_name": "<p>Coca-Cola Şekersiz 330 ML Kutu, 24 Adet</p>\n\n<p>&nbsp;</p>",
      "description": "<h1><strong><span style=\"font-size:12px;\">İçindekiler</span></strong></h1>\n\n<h1><span style=\"font-size:12px;\">\n<p>Su, karbondioksit, renklendirici (karamel), asitliği düzenleyiciler (fosforik asit, sodyum sitrat), tatlandırıcılar*(aspartam***, asesulfam-K, sukraloz), koruyucu (sodyum benzoat), aroma vericiler, kafein (maks. 0.150 g/l). Kafein içerir. Tatlandırıcı içerir. Fenilalanin kaynağı içerir.</p>\n\n<p>Enerji ve Besin Öğeleri 100 ml</p>\n\n<p>Enerji 0,2 kcal (0,8 kJ)</p>\n\n<p>Yağ 0,0 g</p>\n\n<p>Doymuş Yağ 0,0 g</p>\n\n<p>Karbonhidrat 0,0 g</p>\n\n<p>Şeker 0,0 g</p>\n\n<p>Lif 0,0 g</p>\n\n<p>Protein 0,0 g</p>\n\n<p>&nbsp;</p>\n\n<p>&nbsp;</p>\n</span>\n\n<p>&nbsp;</p>\n<span style=\"font-size:12px;\">\n<p>Sodyum 0,0 g</p>\n</span></h1>",
      "status": "available",
      "warranty_period": 0,
      "warranty_type": "day",
      "master": true,
      "extras_exists": false,
      "selectable_extras_exists": false,
      "created_at": "2020-06-20T22:04:27.235+03:00",
      "updated_at": "2020-06-21T22:06:50.523+03:00",
      "taxons": [
        {
          "id": 1,
          "name": "Süpermarket",
          "description": null,
          "visible": true,
          "logo": "",
          "position": 0,
          "full_path": "Kategoriler -> Süpermarket",
          "created_at": "2020-06-20T22:04:26.226+03:00",
          "updated_at": "2020-06-20T22:04:26.226+03:00"
        },
        {
          "id": 30,
          "name": "İçeçek",
          "description": "İçecek ürünleri uygun fiyatlarıyla birlikte HepGelsin'de! Hemen 50 TL ve üzeri ücretsiz kargo fırsatıyla Coca-Cola, Fanta, Sprite, Fuse Tea, Cappy keşfedin",
          "visible": true,
          "logo": "",
          "position": 0,
          "full_path": "Kategoriler -> Süpermarket -> İçeçek",
          "created_at": "2020-06-20T22:04:26.717+03:00",
          "updated_at": "2020-06-20T22:04:27.102+03:00"
        },
        {
          "id": 31,
          "name": "Gazlı İçeçek",
          "description": "Coca Cola ve gazoz çeşitleri uygun fiyatlarıyla birlikte HepGelsin'de! Hemen 50 TL ve üzeri ücretsiz kargo fırsatıyla keşfedin!",
          "visible": true,
          "logo": "",
          "position": 0,
          "full_path": "Kategoriler -> Süpermarket -> İçeçek -> Gazlı İçeçek",
          "created_at": "2020-06-20T22:04:26.738+03:00",
          "updated_at": "2020-06-20T22:04:27.111+03:00"
        },
        {
          "id": 26,
          "name": "Coca-Cola Şekersiz",
          "description": null,
          "visible": true,
          "logo": "",
          "position": 0,
          "full_path": "Markalar -> Coca-Cola -> Coca-Cola Şekersiz",
          "created_at": "2020-06-20T22:04:26.614+03:00",
          "updated_at": "2020-06-20T22:04:27.259+03:00"
        }
      ],
      "option_types": [],
      "product_extras": [],
      "display_price": "64.0",
      "type": "simple",
      "currency": {
        "symbol": "₺",
        "disambiguate_symbol": "₺",
        "subunit_symbol": null,
        "iso_code": "TRY",
        "iso_numeric": "949",
        "name": "Turkish Lira",
        "smallest_denomination": 1,
        "subunit_to_unit": 100,
        "decimal_mark": ",",
        "minor_units": 2
      }
    },
    {
      "id": 4,
      "name": "Coca-Cola Orginal Tat 250 ML Kutu,24 Adet",
      "display_name": "Coca-Cola Orginal Tat 250 ML Kutu,24 Adet",
      "description": "<h2><span style=\"font-size:12px;\">İçindekiler</span></h2>\n\n<h1><span style=\"font-size:12px;\">\n<p>Su, şeker veya fruktoz-glikoz şurubu, karbondioksit, renklendirici (karamel), asitliği düzenleyici (fosforik asit), doğal aroma vericiler, kafein (maks. 0.150 g/l).</p>\n\n<p>Kafein içerir.</p>\n\n<p>Enerji ve Besin Öğeleri 100 ml</p>\n\n<p>Enerji 45 kcal (188,4 kJ)</p>\n\n<p>Yağ 0,0 g</p>\n\n<p>Doymuş Yağ 0,0 g</p>\n\n<p>Karbonhidrat 11,2 g</p>\n\n<p>Şeker 11,2 g</p>\n\n<p>Lif 0,0 g</p>\n\n<p>Protein 0,0 g</p>\n</span>\n\n<p>&nbsp;</p>\n<span style=\"font-size:12px;\">\n<p>Sodyum 0,0 g</p>\n</span></h1>\n<span style=\"font-size:12px;\"> </span>",
      "status": "available",
      "warranty_period": 0,
      "warranty_type": "day",
      "master": true,
      "extras_exists": false,
      "selectable_extras_exists": false,
      "created_at": "2020-06-20T22:04:27.306+03:00",
      "updated_at": "2020-06-21T22:06:50.551+03:00",
      "taxons": [
        {
          "id": 1,
          "name": "Süpermarket",
          "description": null,
          "visible": true,
          "logo": "",
          "position": 0,
          "full_path": "Kategoriler -> Süpermarket",
          "created_at": "2020-06-20T22:04:26.226+03:00",
          "updated_at": "2020-06-20T22:04:26.226+03:00"
        },
        {
          "id": 30,
          "name": "İçeçek",
          "description": "İçecek ürünleri uygun fiyatlarıyla birlikte HepGelsin'de! Hemen 50 TL ve üzeri ücretsiz kargo fırsatıyla Coca-Cola, Fanta, Sprite, Fuse Tea, Cappy keşfedin",
          "visible": true,
          "logo": "",
          "position": 0,
          "full_path": "Kategoriler -> Süpermarket -> İçeçek",
          "created_at": "2020-06-20T22:04:26.717+03:00",
          "updated_at": "2020-06-20T22:04:27.102+03:00"
        },
        {
          "id": 31,
          "name": "Gazlı İçeçek",
          "description": "Coca Cola ve gazoz çeşitleri uygun fiyatlarıyla birlikte HepGelsin'de! Hemen 50 TL ve üzeri ücretsiz kargo fırsatıyla keşfedin!",
          "visible": true,
          "logo": "",
          "position": 0,
          "full_path": "Kategoriler -> Süpermarket -> İçeçek -> Gazlı İçeçek",
          "created_at": "2020-06-20T22:04:26.738+03:00",
          "updated_at": "2020-06-20T22:04:27.111+03:00"
        },
        {
          "id": 24,
          "name": "Coca-Cola Orginal",
          "description": null,
          "visible": true,
          "logo": "",
          "position": 0,
          "full_path": "Markalar -> Coca-Cola -> Coca-Cola Orginal",
          "created_at": "2020-06-20T22:04:26.580+03:00",
          "updated_at": "2020-06-20T22:04:27.118+03:00"
        }
      ],
      "option_types": [],
      "product_extras": [],
      "display_price": "68.4",
      "type": "simple",
      "currency": {
        "symbol": "₺",
        "disambiguate_symbol": "₺",
        "subunit_symbol": null,
        "iso_code": "TRY",
        "iso_numeric": "949",
        "name": "Turkish Lira",
        "smallest_denomination": 1,
        "subunit_to_unit": 100,
        "decimal_mark": ",",
        "minor_units": 2
      }
    }

    ...
  ]
}
```

---

### Search taxon

| Request Type | Route                                        | Query Params  |
| ------------ | -------------------------------------------- | ------------- |
| `GET`        | /whatsgoo/tenants/acme/taxonomies/:id/taxons | q=Kampanyalar |

#### Response | `200`

```Json
{
  "taxons": [
    {
      "id": 44,
      "name": "Kampanyalar",
      "description": null,
      "visible": true,
      "logo": "",
      "position": 0,
      "full_path": "Kategoriler -> Kampanyalar",
      "created_at": "2020-06-20T22:06:17.415+03:00",
      "updated_at": "2020-06-20T22:06:17.415+03:00"
    }
  ]
}

---

```

### Search Taxonomy

| Request Type | Route                             | Query Params |
| ------------ | --------------------------------- | ------------ |
| `GET`        | /whatsgoo/tenants/acme/taxonomies | q=taxonomy   |

#### Response | `200`

```json
{
  "taxonomies": [
    {
      "id": 6,
      "name": "taxonomy 1",
      "code": null,
      "description": "Taxonomy",
      "visible": true,
      "logo": "logo",
      "created_at": "2020-07-17T13:14:27.074+03:00",
      "updated_at": "2020-07-17T13:14:27.074+03:00"
    },
    {
      "id": 7,
      "name": "taxonomy 2",
      "code": null,
      "description": "Taxonomy",
      "visible": true,
      "logo": "logo",
      "created_at": "2020-07-17T13:23:58.815+03:00",
      "updated_at": "2020-07-17T13:23:58.815+03:00"
    },
    {
      "id": 8,
      "name": "taxonomy 3",
      "code": null,
      "description": "Taxonomy",
      "visible": true,
      "logo": "logo",
      "created_at": "2020-07-17T13:24:53.391+03:00",
      "updated_at": "2020-07-17T13:24:53.391+03:00"
    }
  ]
}
```

---

### Get taxons as batch

| Request Type | Route                              |
| ------------ | ---------------------------------- |
| `GET`        | /whatsgoo/tenants/acme/taxons/bulk |

#### Response | `200`

```json
{
  "taxons": [
    {
      "id": 37,
      "name": "Süpermarket",
      "description": null,
      "visible": true,
      "logo": "",
      "position": 0,
      "full_path": "Kategoriler -> Süpermarket",
      "created_at": "2020-06-20T22:06:17.301+03:00",
      "updated_at": "2020-06-20T22:06:17.301+03:00"
    },
    {
      "id": 38,
      "name": "Giyim & Ayakkabı",
      "description": null,
      "visible": false,
      "logo": "",
      "position": 0,
      "full_path": "Kategoriler -> Giyim & Ayakkabı",
      "created_at": "2020-06-20T22:06:17.320+03:00",
      "updated_at": "2020-06-20T22:06:17.320+03:00"
    },
    {
      "id": 39,
      "name": "Elektronik",
      "description": "Mini buzdolapları ve dahası uygun fiyatlarıyla HepGelsin'de! 50 TL ve üzeri ücretsiz kargo fırsatıyla teknolojik ürünleri keşfedin!",
      "visible": true,
      "logo": "",
      "position": 0,
      "full_path": "Kategoriler -> Elektronik",
      "created_at": "2020-06-20T22:06:17.338+03:00",
      "updated_at": "2020-06-20T22:06:17.338+03:00"
    }

    ...
  ]
}


```

---

### Show a taxon

| Request Type | Route                                            |
| ------------ | ------------------------------------------------ |
| `GET`        | /whatsgoo/tenants/acme/taxonomies/:id/taxons/:id |

#### Response | `404`

```json
{
  "error": "Kayıt bulunamadı!"
}
```

---

### Get a taxonomy's taxons

| Request Type | Route                                        |
| ------------ | -------------------------------------------- |
| `GET`        | /whatsgoo/tenants/acme/taxonomies/:id/taxons |

#### Response | `200`

```json
{
  "taxons": [
    {
      "id": 37,
      "name": "Süpermarket",
      "description": null,
      "visible": true,
      "logo": "",
      "position": 0,
      "full_path": "Kategoriler -> Süpermarket",
      "created_at": "2020-06-20T22:06:17.301+03:00",
      "updated_at": "2020-06-20T22:06:17.301+03:00"
    },
    {
      "id": 38,
      "name": "Giyim & Ayakkabı",
      "description": null,
      "visible": false,
      "logo": "",
      "position": 0,
      "full_path": "Kategoriler -> Giyim & Ayakkabı",
      "created_at": "2020-06-20T22:06:17.320+03:00",
      "updated_at": "2020-06-20T22:06:17.320+03:00"
    },
    {
      "id": 39,
      "name": "Elektronik",
      "description": "Mini buzdolapları ve dahası uygun fiyatlarıyla HepGelsin'de! 50 TL ve üzeri ücretsiz kargo fırsatıyla teknolojik ürünleri keşfedin!",
      "visible": true,
      "logo": "",
      "position": 0,
      "full_path": "Kategoriler -> Elektronik",
      "created_at": "2020-06-20T22:06:17.338+03:00",
      "updated_at": "2020-06-20T22:06:17.338+03:00"
    }
    ...
  ]
}

```

---

### Show a tenant

| Request Type | Route                  |
| ------------ | ---------------------- |
| `GET`        | /whatsgoo/tenants/acme |

#### Response | `200`

```json
{
  "tenant": {
    "id": 1,
    "slug": "acme",
    "name": "ACME",
    "description": "Description",
    "industry": "grocery",
    "currency": "TRY",
    "preferences": {},
    "created_at": "2020-06-20T21:38:52.151+03:00",
    "updated_at": "2020-07-19T08:11:30.606+03:00",
    "images": [],
    "address": {
      "id": 1,
      "type": "other",
      "name": "Address",
      "description": null,
      "country_id": 1,
      "country_name": "Türkiye",
      "city_id": 56,
      "city_name": "Samsun",
      "district_id": 830,
      "district_name": "Atakum",
      "neighborhood_name": "Akalan mah",
      "address": "test",
      "phone_number": null,
      "latitude": 0.0,
      "longitude": 0.0,
      "full_address": "test, Akalan mah Atakum/Samsun",
      "created_at": "2020-06-21T23:33:13.712+03:00",
      "updated_at": "2020-07-20T14:33:03.271+03:00"
    },
    "messaging_channels": [
      {
        "id": 130,
        "platform": "call_center",
        "code": "+905333419012",
        "created_at": "2020-07-28T18:52:48.602+03:00",
        "updated_at": "2020-07-28T18:52:48.602+03:00"
      },
      {
        "id": 46,
        "platform": "whatsapp",
        "code": "40720802959",
        "created_at": "2020-06-26T10:06:32.904+03:00",
        "updated_at": "2020-06-26T10:06:32.904+03:00"
      },
      {
        "id": 111,
        "platform": "instagram",
        "code": "azgezercokbilir",
        "created_at": "2020-07-23T07:45:49.496+03:00",
        "updated_at": "2020-07-23T07:45:49.496+03:00"
      },
      {
        "id": 57,
        "platform": "call_center",
        "code": "905333419012",
        "created_at": "2020-07-18T19:50:06.183+03:00",
        "updated_at": "2020-07-18T19:50:06.183+03:00"
      }
    ],
    "working_hours": [
      {
        "id": 3,
        "day": "thursday",
        "opens_at": "00:00",
        "closes_at": "04:00",
        "created_at": "2020-06-23T17:16:00.325+03:00",
        "updated_at": "2020-07-17T23:55:46.333+03:00"
      },
      {
        "id": 4,
        "day": "monday",
        "opens_at": "08:00",
        "closes_at": "09:00",
        "created_at": "2020-07-18T15:29:40.077+03:00",
        "updated_at": "2020-07-18T15:37:32.929+03:00"
      },
      {
        "id": 5,
        "day": "tuesday",
        "opens_at": "10:00",
        "closes_at": "11:00",
        "created_at": "2020-07-20T01:31:38.883+03:00",
        "updated_at": "2020-07-20T01:31:38.883+03:00"
      }
    ],
    "in_working_hours": false
  }
}
```

---

### Search tenant

| Request Type | Route             | Query Params |
| ------------ | ----------------- | ------------ |
| `GET`        | /whatsgoo/tenants | q=tenant     |

#### Response | `200`

```json
{
  "tenants": [
    {
      "id": 5,
      "slug": "doc",
      "name": "Doc Tenant",
      "description": null,
      "industry": "other",
      "currency": "TRY",
      "preferences": {},
      "created_at": "2020-07-17T17:43:04.556+03:00",
      "updated_at": "2020-07-17T17:43:04.556+03:00",
      "images": [],
      "address": null,
      "messaging_channels": [],
      "in_working_hours": false
    },
    {
      "id": 101,
      "slug": "sync",
      "name": "Sync Test",
      "description": "Fuudy Sync Tenant",
      "industry": "other",
      "currency": "TRY",
      "preferences": {},
      "created_at": "2020-07-24T14:13:07.452+03:00",
      "updated_at": "2020-07-24T14:13:07.461+03:00",
      "images": [],
      "address": null,
      "messaging_channels": [
        {
          "id": 121,
          "platform": "call_center",
          "code": "901111111111",
          "created_at": "2020-07-24T14:13:50.060+03:00",
          "updated_at": "2020-07-24T14:13:50.060+03:00"
        },
        {
          "id": 127,
          "platform": "instagram",
          "code": "deeploypro",
          "created_at": "2020-07-24T17:44:15.929+03:00",
          "updated_at": "2020-07-24T17:44:15.929+03:00"
        }
      ],
      "in_working_hours": false
    }
  ]
}
```

---

### Get tenants by industry

| Request Type | Route             | Query params   |
| ------------ | ----------------- | -------------- |
| `GET`        | /whatsgoo/tenants | industry=foods |

#### Response | `200`

```json
{
  "tenants": []
}
```

---

### Get all tenants

| Request Type | Route             |
| ------------ | ----------------- |
| `GET`        | /whatsgoo/tenants |

#### Response | `200`

```json
{
  "tenants": [
    {
      "id": 3,
      "slug": "acme-3",
      "name": "ACME",
      "description": "Description",
      "industry": "grocery",
      "currency": "USD",
      "preferences": {},
      "created_at": "2020-07-17T13:55:22.597+03:00",
      "updated_at": "2020-07-17T13:55:22.597+03:00",
      "images": [],
      "address": null,
      "messaging_channels": [],
      "in_working_hours": false
    },
    {
      "id": 4,
      "slug": "acme-4",
      "name": "ACME",
      "description": "Description",
      "industry": "grocery",
      "currency": "USD",
      "preferences": {},
      "created_at": "2020-07-17T13:58:40.079+03:00",
      "updated_at": "2020-07-17T13:58:40.079+03:00",
      "images": [],
      "address": null,
      "messaging_channels": [],
      "in_working_hours": false
    },
    {
      "id": 1,
      "slug": "acme",
      "name": "ACME",
      "description": "Description",
      "industry": "grocery",
      "currency": "TRY",
      "preferences": {},
      "created_at": "2020-06-20T21:38:52.151+03:00",
      "updated_at": "2020-07-19T08:11:30.606+03:00",
      "images": [],
      "address": {
        "id": 1,
        "type": "other",
        "name": "Address",
        "description": null,
        "country_id": 1,
        "country_name": "Türkiye",
        "city_id": 56,
        "city_name": "Samsun",
        "district_id": 830,
        "district_name": "Atakum",
        "neighborhood_name": "Akalan mah",
        "address": "test",
        "phone_number": null,
        "latitude": 0.0,
        "longitude": 0.0,
        "full_address": "test, Akalan mah Atakum/Samsun",
        "created_at": "2020-06-21T23:33:13.712+03:00",
        "updated_at": "2020-07-20T14:33:03.271+03:00"
      },
      "messaging_channels": [
        {
          "id": 130,
          "platform": "call_center",
          "code": "+905333419012",
          "created_at": "2020-07-28T18:52:48.602+03:00",
          "updated_at": "2020-07-28T18:52:48.602+03:00"
        },
        {
          "id": 46,
          "platform": "whatsapp",
          "code": "40720802959",
          "created_at": "2020-06-26T10:06:32.904+03:00",
          "updated_at": "2020-06-26T10:06:32.904+03:00"
        },
        {
          "id": 111,
          "platform": "instagram",
          "code": "azgezercokbilir",
          "created_at": "2020-07-23T07:45:49.496+03:00",
          "updated_at": "2020-07-23T07:45:49.496+03:00"
        },
        {
          "id": 57,
          "platform": "call_center",
          "code": "905333419012",
          "created_at": "2020-07-18T19:50:06.183+03:00",
          "updated_at": "2020-07-18T19:50:06.183+03:00"
        }
      ],
      "in_working_hours": false
    },
    {
      "id": 2,
      "slug": "bordo-bilisim-2",
      "name": "Bordo Bilişim",
      "description": "Cloud Native Software Development",
      "industry": "technology",
      "currency": "TRY",
      "preferences": {},
      "created_at": "2020-06-24T13:28:29.288+03:00",
      "updated_at": "2020-06-24T13:28:29.288+03:00",
      "images": [],
      "address": null,
      "messaging_channels": [],
      "in_working_hours": false
    },
    {
      "id": 5,
      "slug": "doc",
      "name": "Doc Tenant",
      "description": null,
      "industry": "other",
      "currency": "TRY",
      "preferences": {},
      "created_at": "2020-07-17T17:43:04.556+03:00",
      "updated_at": "2020-07-17T17:43:04.556+03:00",
      "images": [],
      "address": null,
      "messaging_channels": [],
      "in_working_hours": false
    },
    {
      "id": 101,
      "slug": "sync",
      "name": "Sync Test",
      "description": "Fuudy Sync Tenant",
      "industry": "other",
      "currency": "TRY",
      "preferences": {},
      "created_at": "2020-07-24T14:13:07.452+03:00",
      "updated_at": "2020-07-24T14:13:07.461+03:00",
      "images": [],
      "address": null,
      "messaging_channels": [
        {
          "id": 121,
          "platform": "call_center",
          "code": "901111111111",
          "created_at": "2020-07-24T14:13:50.060+03:00",
          "updated_at": "2020-07-24T14:13:50.060+03:00"
        },
        {
          "id": 127,
          "platform": "instagram",
          "code": "deeploypro",
          "created_at": "2020-07-24T17:44:15.929+03:00",
          "updated_at": "2020-07-24T17:44:15.929+03:00"
        }
      ],
      "in_working_hours": false
    }
  ]
}
```

---

### Show a taxonomy

| Request Type | Route                                 |
| ------------ | ------------------------------------- |
| `GET`        | /whatsgoo/tenants/acme/taxonomies/:id |

#### Response | `200`

```json
{
  "taxonomy": {
    "id": 3,
    "name": "Kategoriler",
    "code": null,
    "description": null,
    "visible": true,
    "logo": "",
    "created_at": "2020-06-20T22:06:17.230+03:00",
    "updated_at": "2020-06-20T22:06:17.230+03:00"
  }
}
```

---

### Get tenants taxonomies

| Request Type | Route                             |
| ------------ | --------------------------------- |
| `GET`        | /whatsgoo/tenants/acme/taxonomies |

#### Response | `200`

```json
{
  "taxonomies": [
    {
      "id": 10,
      "name": "foo",
      "code": "bar",
      "description": null,
      "visible": true,
      "logo": "logo",
      "created_at": "2020-07-17T22:19:57.075+03:00",
      "updated_at": "2020-07-17T22:19:57.075+03:00"
    },
    {
      "id": 3,
      "name": "Kategoriler",
      "code": null,
      "description": null,
      "visible": true,
      "logo": "",
      "created_at": "2020-06-20T22:06:17.230+03:00",
      "updated_at": "2020-06-20T22:06:17.230+03:00"
    },
    {
      "id": 4,
      "name": "Markalar",
      "code": null,
      "description": null,
      "visible": true,
      "logo": "",
      "created_at": "2020-06-20T22:06:17.246+03:00",
      "updated_at": "2020-06-20T22:06:17.246+03:00"
    }
    ...
]
}

```

---

### Get tenants announcements

| Request Type | Route                                |
| ------------ | ------------------------------------ |
| `GET`        | /whatsgoo/tenants/acme/announcements |

#### Response | `200`

```json
{
  "announcements": [
    {
      "id": 2,
      "title": "title 2",
      "description": "Test",
      "starts_at": "2020-05-19T01:29:00.000+03:00",
      "ends_at": "2020-05-19T01:29:00.000+03:00",
      "image": "bar",
      "created_at": "2020-07-18T00:23:22.777+03:00",
      "updated_at": "2020-07-18T00:25:14.738+03:00"
    },
    {
      "id": 1,
      "title": "Örnek Duyuru",
      "description": "Lorem ipsum dolor sit amet, consectetur adipiscing elit. In ac malesuada odio. Mauris eu neque tellus. Fusce sagittis lacus sit amet consequat dapibus. Sed eu porttitor erat. Cras eu condimentum sem, quis iaculis enim. Donec quis placerat ante. Aenean facilisis ligula eget condimentum laoreet. Ut tellus est, sodales vel elementum tristique, dignissim at eros.",
      "starts_at": "2020-06-01T00:00:00.000+03:00",
      "ends_at": "2020-07-12T00:00:00.000+03:00",
      "image": "https://thesandrac.files.wordpress.com/2016/01/coke_happiness_orig.jpgw=736",
      "created_at": "2020-06-26T14:03:10.111+03:00",
      "updated_at": "2020-06-26T14:03:10.111+03:00"
    }
  ]
}
```

---
