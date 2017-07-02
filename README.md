# QA-Challenge-SOLTECH-
QA Challenge Repository
public class Soltech { 
	public static void main(String[] args) {
		String exePath = "C:\\Users\\Priyanka\\Desktop\\Server\\chromedriver.exe";
		System.setProperty("webdriver.chrome.driver", exePath);
		WebDriver driver = new ChromeDriver();
		driver.get("http://soltech.net/");
		driver.findElement(By.name("careers")).click();
		driver.findElement(By.name("openpositions")).click();
		driver.findElement(By.name("keywords")).sendKeys("qa");
		driver.findElement(By.name("search")).click();
		driver.findElement(By.name("qualityassuranceautomationengineer")).click();
		driver.findElement(By.name("id")).verify
		
    
	}
}
