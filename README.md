# OchoLoco
OchoLoco Cartas
////////////////////Carta.java///////////////////////
/*
 * Caso de estudio: Ocho loco
 * Repaso del encoque orientado a objetos
 * Taller1
 * Curso de PI
 * EISC Univalle
 * Juan Felipe Alvarado(1745283)
 * Daniel Bermudez (1742658)
 */


package ochoLoco;

import java.util.Random;
import java.util.ArrayList;

// TODO: Auto-generated Javadoc
/**
 * The Class Carta.
 */
public class Carta {
	/*
	 * ArrayList<String> nombreArrayList = new ArrayList<String>();
	 * SubString buacarr
	 * 
	
	public Carta()
	{
		
	}
	
	String[] Palo = {"P", "C", "T", "D"};
	
	String[] Numero = {"A", "2", "3", "4", "5", "6", "7", "8", "9", "10", "J", "Q", "K"};
	*/
	
	/** The mazo. */

	ArrayList<String> mazo = new ArrayList<String>();
	ArrayList<String> baraja = new ArrayList<String>();
	/** The random */
	private Random aleatorio;
	/** The palo. */
	private char palo;
	
	/** The numero. */
	private int numero;
	
	/** The estado. */
	private boolean estado;
	
	/** The carta en juego. */
	private String cartaEnJuego;
	
	/**
	 * Gets the palo.
	 *
	 * @return the palo
	 */
	public char getPalo()
	{
		return palo;
	}
	
	/**
	 * Gets the numero.
	 *
	 * @return the numero
	 */
	public int getNumero()
	{
		return numero;
	}
	
	/**
	 * Gets the estado.
	 *
	 * @return the estado
	 */
	public boolean getEstado()
	{
		return estado;
	}
	
	/** The figura. */
	String figura="";
	
	/** The numeros. */
	String numeros="";
	
	/**
	 * Carta random.
	 *
	 * @return the string
	 */
	public String cartaRandom()
	{
		for(int palo=0; palo<=3; palo++)
		{
			if (palo==0)
			{
				figura="D";
			}
			else 
				if (palo==1)
				{
					figura="T";
				}
				else 
					if (palo==2)
					{
						figura="C";
					}
					else 
						if (palo==3)
						{
							figura="P";
						}
			for (int numero=1; numero<=13; numero++)
			{
				numeros=String.valueOf(numero);
				if (numero==1)
				{
					mazo.add(figura+"A");
				}
				else
					if (numero==10)
					{
						mazo.add(figura+"J");
					}
					else 
						if (numero==11)
						{
							mazo.add(figura+"Q");
						}
						else
							if (numero==12)
							{
								mazo.add(figura+"K");
							}
							else
							{
								mazo.add(figura+numeros);
							}
			}
		}
	return auxCarta;
	}
	
	/** The aux carta. */
	String auxCarta;
/*	public void cartaRandom()
	{
		Random randomPrincipal = new Random();
		int paloRandom = randomPrincipal.nextInt(3);
		int numeroRandom= randomPrincipal.nextInt(12);
		String cartaEnJuego = Palo[paloRandom] + Numero[numeroRandom];
		//return Numero[numeroRandom] + " de " + Palo[paloRandom];
	}
*/
	
	/**
	 * Arma mazo.
	 *
	 * @return the array list
	 */
	public ArrayList<String> armaMazo()
	{
		for(int i=0; i<=51; i++)
		{
			mazo.add(i, cartaRandom());
		}
		return mazo;
	}
	
	/**
	 * Repartir cartas.
	 */
	public ArrayList<String> repartirCartas()
	{
		int numeroAleatorio=aleatorio.nextInt(mazo.size());
		for(int i=0; i<=7; i++)
		{
			baraja.add(mazo.get(numeroAleatorio));
			mazo.remove(numeroAleatorio);
			
		}
		return baraja;
	}
	
	

}
//////////////////////COntrol.java///////////////////////

package ochoLoco;
import java.util.Random;

public class Control {
	public String carta()
	{
		
		return " ";
	}

}
///////////////////////////////////////////Main///////////////////////////////////////////////////////////////
/*
 * Caso de estudio: Ocho loco
 * Repaso del encoque orientado a objetos
 * Taller1
 * Curso de PI
 * EISC Univalle
 * Juan Felipe Alvarado(1745283)
 * Daniel Bermudez (1742658)
 */

package ochoLoco;

public class Main {

	public static void m/*
 * Caso de estudio: Ocho loco
 * Repaso del encoque orientado a objetos
 * Taller1
 * Curso de PI
 * EISC Univalle
 * Juan Felipe Alvarado(1745283)
 * Daniel Bermudez (1742658)
 */

package ochoLoco;

public class VistaConsola {

}
ain(String[] args) {
		// TODO Auto-generated method stub

	}

}
/////////////////////////////////////////VistaConsola.java///////////////////////////////////////////
/*
 * Caso de estudio: Ocho loco
 * Repaso del encoque orientado a objetos
 * Taller1
 * Curso de PI
 * EISC Univalle
 * Juan Felipe Alvarado(1745283)
 * Daniel Bermudez (1742658)
 */

package ochoLoco;

public class VistaConsola {

}
