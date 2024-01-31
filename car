class Car {
    int maxSpeed = 0;
    num price = 0;
    String name = '';
  
    Car (int s, num p, String n) {
        this.maxSpeed = s;
        this.price = p;
        this.name = n;
    }
  
    num saleCar() {
        price = price * 0.9;
        return price;
    }
}

void main() {
    Car bmw = Car(320, 100000, 'BMW');
    Car benz = Car(250, 70000, 'BENZ');
    Car ford = Car(200, 80000, 'FORD');
  
    bmw.saleCar();
    bmw.saleCar();
    bmw.saleCar();
  
    print(bmw.price);
}
