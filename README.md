# Online-Shopping-Cart-System-in-Dart
shopping cart system
class item {
string name;
double price;

item(this.name, this.price);
}
class shoppingCart {
list<item>items;
double taxarate;
shoppingcart({required this.itemsthis.taxrate=0.00});
