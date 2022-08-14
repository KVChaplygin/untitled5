package seljavatest;

import org.openqa.selenium.chrome.ChromeDriver;

public class Test {
    @org.junit.jupiter.api.Test
    public void firstTest(){
        System.setProperty("webdriver.chrome.driver","C:\\driver\\chromedriver.exe");
        ChromeDriver driver = new ChromeDriver();
        driver.get("https://www.youtube.com/");
    }
}
