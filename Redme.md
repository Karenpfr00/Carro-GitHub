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