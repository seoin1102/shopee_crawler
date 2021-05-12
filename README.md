# shopee_crawler

## Usage

### 1. Run 'crawler.py'
```sh
1. store update / 2. item update
```
If you want to bring the latest products in the store, enter '1' and enter the number of products to bring.
Enter '2' if you want to update the information of the products entered at the endpoint.

The store's latest product information is stored in the file 'item_1.json'.
Among them, products with zero stock are stored in the 'zero_1.json' file.

Updated product information is stored in the 'item_2.json' file.
Among them, products with zero stock are stored in the 'zero_2.json' file.
Deleted products is stored in the 'delete.json' file.

## item.json example

```python
{"itemid": 175801231,
  "price_max_before_discount": 17500000000,
  "item_status": "normal",
  "can_use_wholesale": false,
  "brand_id": null,
  "show_free_shipping": true,
  "estimated_days": 2,
  "is_hot_sales": null,
  "is_slash_price_item": false,
  "upcoming_flash_sale": null,
  "slash_lowest_price": null,
  "is_partial_fulfilled": false,
  "condition": 1,
  "show_original_guarantee": false,
  "add_on_deal_info": null,
  "is_non_cc_installment_payment_eligible": false,
  "categories": [
      {
          "display_name": "Thời Trang Nữ",
          "catid": 77,
          "image": null,
          "no_sub": false,
          "is_default_subcat": false,
          "block_buyer_platform": null
      }
  ],
  "ctime": 1489340701,
  "name": "[Mã FATHANG5 giảm 10K đơn 50K]  Chân váy Tennis (Có size to) HÀNG CÓ SẴN",
  "show_shopee_verified_label": true,
  "userid": null,
  "size_chart": null,
  "is_pre_order": false,
  "service_by_shopee_flag": null,
  "historical_sold": 2940,
  "reference_item_id": "",
  "recommendation_info": null,
  "bundle_deal_info": null,
  "bundle_deal_id": 0,
  "has_lowest_price_guarantee": false,
  "shipping_icon_type": 0,
  "images": [
      "41271b7e772ebb2098d57b142979d7d3"
  ],
  "price_before_discount": 17500000000,
  "cod_flag": 0,
  "catid": 77,
  "is_official_shop": false,
  "coin_earn_label": null,
  "hashtag_list": null,
  "sold": 22,
  "makeup": null,
  "item_rating": {
      "rating_star": 4.985868,
      "rating_count": [
          1491
      ],
      "rcount_with_image": 331,
      "rcount_with_context": 877
  },
  "show_official_shop_label_in_title": false,
  "discount": "3%",
  "reason": null,
  "label_ids": [
      1001061
  ],
  "has_group_buy_stock": false,
  "other_stock": 0,
  "deep_discount": null,
  "attributes": [
      {
          "is_pending_qc": true,
          "idx": 1,
          "value": "Váy xếp li",
          "id": 10475,
          "is_timestamp": false,
          "name": "Phong cách"
      }
  ],
  "last_active_time": null,
  "badge_icon_type": 0,
  "liked": false,
  "is_on_flash_sale": null,
  "cmt_count": 1548,
  "image": "41271b7e772ebb2098d57b142979d7d3",
  "recommendation_algorithm": null,
  "is_cc_installment_payment_eligible": false,
  "shopid": 13799408,
  "normal_stock": 62,
  "video_info_list": [],
  "installment_plans": null,
  "view_count": 7653,
  "voucher_info": null,
  "current_promotion_has_reserve_stock": false,
  "liked_count": 4697,
  "show_official_shop_label": false,
  "price_min_before_discount": 17500000000,
  "show_discount": 3,
  "preview_info": null,
  "flag": 2,
  "exclusive_price_info": null,
  "current_promotion_reserved_stock": 0,
  "wholesale_tier_list": [],
  "group_buy_info": null,
  "shopee_verified": true,
  "item_has_post": false,
  "hidden_price_display": null,
  "transparent_background_image": "",
  "welcome_package_info": null,
  "discount_stock": 62,
  "coin_info": {
      "spend_cash_unit": 100000,
      "coin_earn_items": []
  },
  "is_adult": false,
  "currency": "VND",
  "raw_discount": 3,
  "is_preferred_plus_seller": false,
  "is_category_failed": false,
  "price_min": 16975000000,
  "can_use_bundle_deal": false,
  "cb_option": 0,
  "brand": "No brand",
  "stock": 62,
  "status": 1,
  "price_max": 16975000000,
  "spl_info": null,
  "is_group_buy_item": null,
  "description": "Chất kaki mềm đẹp\r\nHàng chuẩn shop \r\nChân váy hàng loại 1 cao cấp, kẻ Caro",
  "flash_sale": null,
  "models": [
      {
          "itemid": 175801231,
          "status": 1,
          "current_promotion_reserved_stock": 0,
          "name": "C01/SỌC XANH ĐEN,XS",
          "promotionid": 1243920281,
          "price": 16975000000,
          "price_stocks": [
              {
                  "model_id": 2407276877,
                  "stockout_time": 1617686038,
                  "region": "VN",
                  "rebate": 0,
                  "price": 16975000000,
                  "promotion_type": 301,
                  "allocated_stock": 0,
                  "shop_id": 13799408,
                  "end_time": 1625072340,
                  "stock_breakdown_by_location": [],
                  "item_id": 175801231,
                  "promotion_id": 1243920281,
                  "purchase_limit": 0,
                  "start_time": 1617686100,
                  "stock": 0
              },
              {
                  "model_id": 2407276877,
                  "stockout_time": 0,
                  "region": "VN",
                  "rebate": 0,
                  "price": 17500000000,
                  "promotion_type": 0,
                  "allocated_stock": 0,
                  "shop_id": 13799408,
                  "end_time": null,
                  "stock_breakdown_by_location": [],
                  "item_id": 175801231,
                  "promotion_id": 0,
                  "purchase_limit": 0,
                  "start_time": null,
                  "stock": 2
              }
          ],
          "current_promotion_has_reserve_stock": false,
          "currency": "VND",
          "normal_stock": 2,
          "extinfo": {
              "seller_promotion_limit": 0,
              "has_shopee_promo": false,
              "group_buy_info": null,
              "holiday_mode_old_stock": null,
              "tier_index": [
                  0,
                  0
              ],
              "seller_promotion_refresh_time": 1625072340
          },
          "has_gimmick_tag": false,
          "price_before_discount": 17500000000,
          "modelid": 2407276877,
          "sold": 67,
          "stock": 2}
```

## delete.json example

```python

{"2686527327": "383300809"}
```
The key contains the ID of the deleted product, and the value contains the store ID of the deleted product.


### 2. Run 'send_json.py'
```sh
file name:
```
Enter the name of the file you want to send. For example, if you want to update the products stored on the endpoint, type 'item_2'.
