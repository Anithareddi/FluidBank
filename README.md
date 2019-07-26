# FluidBank
This project is a simple java based banking appplication
package com.java.main.Bank.Ui_testing;

import org.openqa.selenium.By;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;
import org.testng.annotations.AfterClass;
import org.testng.annotations.BeforeClass;
import org.testng.annotations.Test;

/**
 * @author Anitha
 *
 */
public class App {
	public static WebDriver driver ;
	
@BeforeClass
public void setup() {
	driver= new ChromeDriver();
	System.getProperty(("user.dir") +" \\Ui-testing\\Driver\\chromedriver.exe");
	driver.get("https://fluid.co.uk/");
}

@Test
public void RegPage() {
	driver.findElement(By.xpath("")).click();
	driver.findElement(By.id(""));
	
}
public void homePage() {
	
}
@AfterClass
public void tearDown() {
	
}
}
