//	<!-- below 2 dependences for AutomationSeleniumTesting & AutoWebdriverManager -->
//	<dependency>
//	<groupId>org.seleniumhq.selenium</groupId>
//	<artifactId>selenium-java</artifactId>
//	<version>4.0.0-alpha-3</version>
//</dependency>
//<dependency>
//	<groupId>io.github.bonigarcia</groupId>
//	<artifactId>webdrivermanager</artifactId>
//	<version>3.7.1</version>
	// keep below dependency also..if u get any exceptions
//</dependency>
//<!-- <dependency> <groupId>org.slf4j</groupId> <artifactId>slf4j-simple</artifactId> 
//	<version>1.7.21</version> </dependency> -->

import org.openqa.selenium.By;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;
import org.openqa.selenium.chrome.ChromeOptions;

public static void main(String[] args) throws InterruptedException {
		System.out.println("hello");
//		WebDriverManager.chromedriver().setup();
//		ChromeOptions options = new ChromeOptions();
//		options.addArguments("--headless");
		System.setProperty("webdriver.chrome.driver", "E:/Downlodes/chromedriver.exe");
		System.out.println("Please Wait.......");
		WebDriver driver = new ChromeDriver();

		System.out.println("Fetching IP address.....");
		driver.get("https://web.whatsapp.com/");
		Thread.sleep(10000);
		driver.findElement(By.xpath("//div[@role='textbox']")).sendKeys("Anil Bharath Dvp");
		driver.findElement(By.xpath("//span[@class='matched-text i0jNr']")).click();
		for (int i = 0; i < 100; i++) {
			driver.findElement(By.xpath("//div[@title='Type a message']")).sendKeys("hello");
			driver.findElement(By.xpath("//span[@data-testid='send']")).click();
		}
	}
