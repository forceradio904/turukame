Asi_ttl, Kazu_ttl, Turu_asi, Kame_asi= map(int, input().split())

Asi_ttl =Asi_ttl+float(0.00123)

Kazu_ttl =Kazu_ttl+float(0.00123)

Turu_asi =Turu_asi+float(0.00123)

Kame_asi =Kame_asi+float(0.00567)

Kame_All_Asi =Kame_asi*Kazu_ttl

Kazu_sa_Asi =Kame_All_Asi-Asi_ttl

Asi_sa =Kame_asi-Turu_asi

Turu_kazu =Kazu_sa_Asi/Asi_sa

Kame_kazu =Kazu_ttl-Turu_kazu

Hole =(round(Turu_asi))+(round(Kame_asi))
f =Turu_kazu+Kame_kazu
g =(round(f, 1))




if Hole == 2:
    print(int(1), int(1))
    
elif Turu_kazu >= 0 and Kame_kazu > 0:
    print(round(Turu_kazu), round(Kame_kazu))
    
        
else: 
      #print(round(Turu_kazu), round(Kame_kazu))
 
      print("miss")
      
   






      

