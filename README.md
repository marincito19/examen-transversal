# examen-transversal
productos = {'8475hd'}['hp,15.6','8gb','dd','it','intel core i7', 'nvidia gtx1050']
'2175hd'['acer',14,'4gb','ssd','16gb','ssd','256','intel core i7','nvidiagtx1050 ']
'jjffhd'['asus',14,'16gb','ssd','256gb','intel core i5','nvidia rtx2080ti']


stock = {'8475hd'}[387990,10],'2175hd'[327990,4],'jjffhd'[424990,1]
'fgdxfhd'[664990,21],'123fhd'[290890,32],'352fhd'[444990,7]
'gf75hd'[749990,2],'uwu131hd'[349990,1],'fs1230hd'[249990.0]



def stock_marca(marca):
    total = 0
    for modelo, datos in productos.items():
        if datos [0].lower() == marca.lower():
            total += stock[modelo][1]
            print(f" el stock es:{total}")

            def busqueda_precio(p_min,p-max):
                try:
                    p_min = int(p_min)
                    p_max = int(p_max)
                except:
                    print("debe ingresar valoresenteros")
                    return
                encontrados = []
                for modelo, (precio, cantidad) in stock.items():
                    if p_min <= precio <= p_max and cantidad 
                    marca = productos[modelo][0]
