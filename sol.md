-- se supone que las transferencias con referencia las deudas se haran en un futuro en un tiempo determinado  


tranferir_capitales(Julieta, Ulises, 400'AMZ');
	if error then 
		rollback
	if succes then
		comit
transferir_efectivo(Ulises, Julieta, 66048.20'MX')
	if error
		rollback
	if succes
		comit
end



transferir_capitales(Sebas Doulong, Javier Orcazas, 1200'Gamestop')
	if error then
		rollback
	if succes then 
		comit
transferir_deuda(Javier Orcazas, Sebas Doulong, 2998.12'MX')
	if error then
		rollback
	if succes then 
		comit
transferir_efectivo(Javier Orcazas, Sebas Doulong, 716.76'MX')
	if error then
		rollback
	if succes then 
		comit

end	



transferencia_divisas(DJ DElegado, Frida Kaori, 20000'USD') && transferencia_deuda(DJ Delgado, Frida Kaori, 300)
	if error then
		rollback
	if succes then 
		comit
transferencia_efectivo(Frida Kaori, DJ Delgado, 50400'MX')
	if error then
		rollback
	if succes then 
		comit

end
