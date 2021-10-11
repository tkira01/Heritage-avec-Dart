class User{
  dynamic prenom='Fatima';
  dynamic nom='Agne';
  dynamic adresse='Grand_Dakar';
  
  void manger(){
    print("je mange");
      }
  
  void etudier(){
    print("j'etudie Flutter");
  }
  
  
  }
class Apprenant extends User{
  
  void info(){
    print(manger);
  }
    
    
    int numero=0;
    Apprenant(this.numero);
    
  }

  void main(){ 
    
    Apprenant a= Apprenant (773068637);
    
    print("prenom=${a.prenom} nom=${a.nom} adresse=${a.adresse} numero=${a.numero}");
  }
