# resolu-otelaJAVA
Código para mostrar a resolução da tela em java

package resolucaosistema;

import java.awt.Dimension;
import java.awt.Toolkit;


public class ResolucaoSistema {
public static void main(String[] args) {

Toolkit tela = Toolkit.getDefaultToolkit();
    Dimension d = tela.getScreenSize();
    System.out.println("Resolução do Display: "+d.width+" x "+d.height);
    
    }
    
}
