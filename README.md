# Git-Github
#selenium program to open linked in 
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;

public class DemoSel {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		System.setProperty("webdriver.chrome.driver", "C:\\TINA\\selenium\\chromedriver_win32\\chromedriver.exe");
        WebDriver driver=new ChromeDriver();
        driver.get("https://www.google.com");//Hit the correct url
        System.out.println(driver.getTitle());//Validate the title
        System.out.println( driver.getCurrentUrl());//validate the url
      //  System.out.println(driver.getPageSource());//Print page source
        driver.navigate().to("https://www.linkedin.com/?trk=msn-top-in");
	}
	
	

}
