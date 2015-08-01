package mypack;

import org.openqa.selenium.By;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.WebElement;
import org.openqa.selenium.firefox.FirefoxDriver;
import org.openqa.selenium.support.ui.Select;

public class SpicejetBooking {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		WebDriver driver = new FirefoxDriver();
		driver.manage().window().maximize();
		driver.get("https://book.spicejet.com/Register.aspx");
		
		/*
		 * Login Information*/
		//Username
		driver.findElement(By.xpath("//*[@id='CONTROLGROUPREGISTERVIEW_MemberInputRegisterView_TextBoxAgentUserName']")).sendKeys("Moganarangan");
		//Password
		driver.findElement(By.xpath("//*[@id='CONTROLGROUPREGISTERVIEW_MemberInputRegisterView_PasswordFieldAgentPassword']")).sendKeys("Mogan12345");
		//Re Enter Password
		driver.findElement(By.xpath("//*[@id='CONTROLGROUPREGISTERVIEW_MemberInputRegisterView_PasswordFieldPasswordConfirm']")).sendKeys("Mogan12345");
		
		/*
		 * Personal Details*/
		//Title
		WebElement title = driver.findElement(By.xpath("//*[@id='CONTROLGROUPREGISTERVIEW_PersonInputRegisterView_DropDownListTitle']"));
		Select title1 = new Select(title);
		title1.selectByValue("MR");
		//First name
		driver.findElement(By.xpath("//*[@id='CONTROLGROUPREGISTERVIEW_PersonInputRegisterView_TextBoxFirstName']")).sendKeys("Moganarangan");
		//Last Name
		driver.findElement(By.xpath("//*[@id='CONTROLGROUPREGISTERVIEW_PersonInputRegisterView_TextBoxLastName']")).sendKeys("M");
		//BirthDate
		WebElement day = driver.findElement(By.xpath("//*[@id='CONTROLGROUPREGISTERVIEW_PersonInputRegisterView_DropDownListDOBDay']"));
		WebElement month = driver.findElement(By.xpath("//*[@id='CONTROLGROUPREGISTERVIEW_PersonInputRegisterView_DropDownListDOBMonth']"));
		WebElement year = driver.findElement(By.xpath("//*[@id='CONTROLGROUPREGISTERVIEW_PersonInputRegisterView_DropDownListDOBYear']"));
		
		Select day1 = new Select(day);
		day1.selectByValue("1");
		
		Select month1 = new Select(month);
		month1.selectByValue("1");
		
		Select year1 = new Select(year);
		year1.selectByValue("1990");
		
		//Nationality
		WebElement nationality = driver.findElement(By.xpath("//*[@id='CONTROLGROUPREGISTERVIEW_PersonInputRegisterView_DropDownListNationality']"));
		Select nationality1 = new Select(nationality);
		nationality1.selectByValue("IN");
		
		//Contact Details
		//Address line-1
		driver.findElement(By.xpath("//*[@id='CONTROLGROUPREGISTERVIEW_PersonInputRegisterView_TextBoxStreetAddress1']")).sendKeys("No-10, FIrst Street");
		//Address Line-2
		driver.findElement(By.xpath("//*[@id='CONTROLGROUPREGISTERVIEW_PersonInputRegisterView_TextBoxStreetAddress2']")).sendKeys("Asthinapuram");
		//Country
		WebElement country = driver.findElement(By.xpath("//*[@id='CONTROLGROUPREGISTERVIEW_PersonInputRegisterView_DropDownListCountry']"));
		Select country1 = new Select(country);
		country1.selectByValue("IN");
		
		//State/Province
		WebElement state = driver.findElement(By.xpath("//*[@id='CONTROLGROUPREGISTERVIEW_PersonInputRegisterView_DropDownListState']"));
		Select state1 = new Select(state);
		state1.selectByValue("IN|TN");
				
		//Town or City
		driver.findElement(By.xpath("//*[@id='CONTROLGROUPREGISTERVIEW_PersonInputRegisterView_TextBoxTownCity']")).sendKeys("Chennai");
		
		//Zip / Postal Code
		driver.findElement(By.xpath("//*[@id='CONTROLGROUPREGISTERVIEW_PersonInputRegisterView_TextBoxPostalCode']")).sendKeys("600064");
		
		//Mobile Phone
		driver.findElement(By.xpath("//*[@id='CONTROLGROUPREGISTERVIEW_PersonInputRegisterView_TextBoxFirstPhone']")).sendKeys("9884347840");
		
		
		//Email Address
		driver.findElement(By.xpath("//*[@id='CONTROLGROUPREGISTERVIEW_PersonInputRegisterView_TextBoxEmail']")).sendKeys("moganarangan@gmail.com");
		
		//Checkbox
		driver.findElement(By.xpath("//*[@id='CONTROLGROUPREGISTERVIEW_PersonInputRegisterView_CheckBoxPromoOpt']")).click();
						
		//Register - Submit Button
		driver.findElement(By.xpath("//*[@id='CONTROLGROUPREGISTERVIEW_ButtonSubmit']")).click();
				
		
		
	}

}
