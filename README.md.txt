# Guitarra_java

public class Guitarra {
    private String numeroSerie;
    private String fabricante;
    private String modelo;
    private String tipo;
    private String madeira;
    private double preco;

    // Construtor
    public Guitarra(String numeroSerie, String fabricante, String modelo, String tipo, String madeira, double preco) {
        this.numeroSerie = numeroSerie;
        this.fabricante = fabricante;
        this.modelo = modelo;
        this.tipo = tipo;
        this.madeira = madeira;
        this.preco = preco;
    }

    // Métodos getters e setters
    public String getNumeroSerie() {
        return numeroSerie;
    }

    public void setNumeroSerie(String numeroSerie) {
        this.numeroSerie = numeroSerie;
    }

    public String getFabricante() {
        return fabricante;
    }

    public void setFabricante(String fabricante) {
        this.fabricante = fabricante;
    }

    public String getModelo() {
        return modelo;
    }

    public void setModelo(String modelo) {
        this.modelo = modelo;
    }

    public String getTipo() {
        return tipo;
    }

    public void setTipo(String tipo) {
        this.tipo = tipo;
    }

    public String getMadeira() {
        return madeira;
    }

    public void setMadeira(String madeira) {
        this.madeira = madeira;
    }

    public double getPreco() {
        return preco;
    }

    public void setPreco(double preco) {
        this.preco = preco;
    }

    // Método para exibir informações
    public void exibirInformacoes() {
        System.out.println("Número de Série: " + numeroSerie);
        System.out.println("Fabricante: " + fabricante);
        System.out.println("Modelo: " + modelo);
        System.out.println("Tipo: " + tipo);
        System.out.println("Madeira: " + madeira);
        System.out.println("Preço: R$" + preco);
    }

    // Método principal para testar a classe
    public static void main(String[] args) {
        Guitarra minhaGuitarra = new Guitarra("12345", "Fender", "Stratocaster", "Elétrica", "Mogno", 2500.00);
        minhaGuitarra.exibirInformacoes();
    }
}


