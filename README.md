package org.icecream;

public class Ice {
	private String color,type,brand,flavour;
	private int price;
	
	public Ice(String color,String type,String brand,String flavour,int price) {
		this.color=color;
		this.type=type;
		this.brand=brand;
		this.flavour=flavour;
		this.price=price;
	}
	public String getType() {
		return type;
	}
	public void setType(String type) {
}
	public void setPrice(int price) {
		this.price=price;
	}
	public String getColor() {
		return color;
	}
	public void setColor(String color) {
		this.color=color;
	}
	public String getBrand() {
		return brand;
	}
	public void setBrand(String brand) {
		this.brand=brand;
	}
 public String getFlavour() {
		return flavour;
	}
	public void  serFlavour(String flavour) {
		this.flavour=flavour;
	}
	public int getPrice() {
		return price;
	}
	public static void main(String[] args) {
		Ice i=new Ice("bule","chocobar ice","Arunice","vanilla",150);
		i.setType("cone ice");
		i.setPrice(120);
		System.out.println("Price is"+i.getPrice());
		System.out.println("Color is"+i.getColor());
		System.out.println("Brand is"+i.getBrand());
		System.out.println("Flavour is"+i.getFlavour());
	}
}
