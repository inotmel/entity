package entity;

public class Guest {
  private String name;
  private String address;
  private String gender;
  private String age;
  private String contactNum;
  private String email;
  
  public Guest(String name, String address, String gender, String age, String contactNum, String email){
    this.name = name;
    this.address = address;
    this.gender = gender;
    this.age = age;
    this.contactNum = contactNum;
    this.email = email;
    
    }
    
    public Guest(){
    }
    
    public String getName(){
      return name;
    }
    public void setName(String name){
      this.name = name;
    }
    public String getAddress(){
      return address;
    }
    public void setAddress(String address){
      this.address = address;
    }
    public String getGender(){
      return gender;
    }
    public void setGender(String gender){
      this.gender = gender;
    }
    public String getAge(){
      return age;
    }
    public void setAge(String age){
      this.age = age;
    }
    public String getcontactNum(){
      return contactNum;
    }
    public void setcontactNum(String contactNum){
      this.contactNum = contactNum;
    }
    public String getEmail(){
      return email;
    }
    public void setEmail(String email){
      this.email = email;
    }
    
  }
    
    
    
    
    
    
    
    
    
  
