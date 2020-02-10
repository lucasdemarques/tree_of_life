
/* A simple AND gate
File: and.v              */

module andgate
	(a, b, y); //sinais de entrada e said

	input a, b;          	  // INPUTS
	output y;		  // OUTPUTS

	wire and_temp;
	assign and_temp = a & b;	  // ATRIBUTO OPERAÇÃO
	assign  y = and_temp;  	  // ATRIBUTO

endmodule 
