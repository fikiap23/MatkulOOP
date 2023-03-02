class Warga {
    String nama;
   
    String kemampuan = "Kemampuan tatap!";
    boolean latihSkill=false;

    void beriLatihanSkill(){
        this.latihSkill=true;
    }

    void beriMotivasi(){
        if (this.latihSkill==true) {
            this.kemampuan="Kemampuan bertambah!";
        }
    } 
    
    void cekKemampuan(){
        System.out.println( this.nama+": "+this.kemampuan);
    }
}

class simulasiWarga{
    public static void main(String[] args) {
        Warga warga1 =new Warga();
        warga1.nama = "Budi";
        warga1.beriLatihanSkill();
        warga1.beriMotivasi();
        warga1.cekKemampuan();
        
        Warga warga2 =new Warga();
        warga2.nama = "Andi";
        warga2.beriMotivasi();
        warga2.cekKemampuan();
    }
}



