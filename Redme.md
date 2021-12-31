import Modelo.Carro;

public class Main {

    public static void main(String[] args){
        Carro carro = new Carro();

        carro.setModelo("Xsara Picasso");
        carro.setPortas(4);
        carro.setAnoFabricação(2012);
        carro.setChassi(1234);
        carro.setCombustivel(550);
        carro.setCor("Prata");
        carro.setFabricante("Citroen");
        carro.setPreço(25.115);


        System.out.println("   ---INFORMAÇÕES DO CARRO---");
        System.out.println("Modelo: " +carro.getModelo());
        System.out.println("Fabricante: " + carro.getFabricante());
        System.out.println("Ano de Fabricação: " + carro.getAnoFabricação());
        System.out.println("Cor: " + carro.getCor());
        System.out.println("Capacidade de Combustível: " + carro.getCombustivel() + " L");
        System.out.println("Quantidade de Portas:" + carro.getPortas());
        System.out.println("Preço: R$" + carro.getPreço());
        System.out.println("Númedo do Chassi: " + carro.getChassi());
    }
}


package Modelo;

public class Carro {
    private String modelo;
    private String fabricante;
    private String cor;
    private double preço;
    private int portas;
    private int chassi;
    private int anoFabricação;
    private double combustivel;

        public void setPortas(int portas){
            this.portas = portas;
        }

    public void setChassi(int chassi) {
        this.chassi = chassi;
    }

    public void setAnoFabricação(int anoFabricação) {
        this.anoFabricação = anoFabricação;
    }

    public void setCombustivel(double combustivel) {
        this.combustivel = combustivel;
    }

    public void setModelo(String modelo) {
        this.modelo = modelo;
    }

    public void setFabricante(String fabricante) {
        this.fabricante = fabricante;
    }

    public void setCor(String cor) {
        this.cor = cor;
    }

    public void setPreço(double preço) {
        this.preço = preço;
    }

    public int getPortas() {
        return portas;
    }

    public int getChassi() {
        return chassi;
    }

    public int getAnoFabricação() {
        return anoFabricação;
    }

    public double getCombustivel() {
        return combustivel;
    }

    public String getModelo() {
        return modelo;
    }

    public String getFabricante() {
        return fabricante;
    }

    public String getCor() {
        return cor;
    }

    public double getPreço() {
        return preço;
    }
}
