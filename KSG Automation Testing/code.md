# KSG-Application-Complete-Testing




# AUTOMATION TESTING USING SELENIUM WEBDRIVER WITH TESTNG FRAMEWORK

* Name: Manti Lakshmi narayana
* Employee mail id: lakshminarayanamanti@btsinfotech.com 
* Website: `https://www.ksgcollege.com/`

## 1.ELEMENTS CLASS POM CLASS
=========================================================================================================================

package package1;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.WebElement;
import org.openqa.selenium.support.FindBy;
import org.openqa.selenium.support.PageFactory;

public class Elements {

	@FindBy(xpath = "(//div[@class='header-contact'])[2]")
	private WebElement CollegeLogo;
	@FindBy(xpath = "//a[text()='ksgprincipal@gmail.com']")
	private WebElement CollegeMailID;
	@FindBy(xpath = "//span[text()='+91-8148277777']")
	private WebElement CollegeContactNumber;
	@FindBy(xpath = "//i[@class='fa fa-facebook-f']")
	private WebElement FacebookLink_btn;
	@FindBy(xpath = "//i[@class='fa fa-youtube']")
	private WebElement YoutubeLink_btn;
	@FindBy(xpath = "//i[@class='fa fa-instagram']")
	private WebElement InstagramLink_btn;
	@FindBy(xpath = "//a[text()='Staff Login']")
	private WebElement StaffLogin_btn;
	@FindBy(xpath = "//a[text()='Student Login']")
	private WebElement StudentLogin_btn;
	@FindBy(xpath = "//a[text()='Alumni']")
	private WebElement Alumni_btn;
	@FindBy(xpath = "//a[text()='Home']")
	private WebElement Nav_Home_btn;
	@FindBy(xpath = "//a[text()='COLLEGE']")
	private WebElement Nav_College_btn;
	@FindBy(xpath = "//a[text()='Course']")
	private WebElement Nav_Course_btn;
	@FindBy(xpath = "//a[text()='gallery']")
	private WebElement Nav_Gallery_btn;
	@FindBy(xpath = "//a[text()='Facilities ']")
	private WebElement Nav_Facilities_btn;
	@FindBy(xpath = "//a[text()='Campus']")
	private WebElement Nav_Campus_btn;
	@FindBy(xpath = "//a[text()='Placement']")
	private WebElement Nav_Placement_btn;
	@FindBy(xpath = "//a[text()='Service']")
	private WebElement Nav_Service_btn;
	@FindBy(xpath = "//a[text()='NIRF']")
	private WebElement Nav_Nirf_btn;
	@FindBy(xpath = "//a[text()='Contact']")
	private WebElement Nav_Contact_btn;
	@FindBy(xpath = "//a[text()='Online Payment']")
	private WebElement Nav_OnlinePayment_btn;
	@FindBy(xpath = "//a[text()='DONATION']")
	private WebElement Nav_Donation_btn;
	@FindBy(xpath = "(//ul[@class='sub-menu'])[1]")
	private WebElement Nav_College_btnSubmenu;
	@FindBy(xpath = "(//ul[@class='sub-menu'])[2]")
	private WebElement Nav_Course_btnSubmenu;
	@FindBy(xpath = "(//ul[@class='sub-menu'])[3]")
	private WebElement Nav_Campus_btnSubmenu;
	@FindBy(xpath = "(//ul[@class='sub-menu'])[4]")
	private WebElement Nav_Placement_btnSubmenu;
	@FindBy(xpath = "(//ul[@class='sub-menu'])[5]")
	private WebElement Nav_Service_btnSubmenu;
	@FindBy(xpath = "(//ul[@class='sub-menu'])[6]")
	private WebElement Nav_Nirf_btnSubmenu;
	@FindBy(id = "exampleInputUsername")
	private WebElement StaffLogin_username;
	@FindBy(id = "exampleInputPassword")
	private WebElement StaffLogin_Password;
	@FindBy(id = "user-checkbox")
	private WebElement StaffLogin_Checkbox;
	@FindBy(xpath = "//label[text()='Remember me']")
	private WebElement StaffLogin_RememberMe;
	@FindBy(xpath = "//button[@type='submit']")
	private WebElement StaffLogin_SignIn_btn;
	@FindBy(className = "lobibox-notify-msg")
	private WebElement StaffLogin_ErrorMessage;
	@FindBy(xpath = "//h2[text()='Alumni']")
	private WebElement Alumni_pageHeading;
	@FindBy(className = "main-btn")
	private WebElement Alumni_Registration_btn;
	@FindBy(xpath = "//a[text()='About KSG']")
	private WebElement College_List_AboutKSG;
	@FindBy(xpath = "//a[text()='Management']")
	private WebElement College_List_Management;
	@FindBy(xpath = "//h2[text()='Management']")
	private WebElement College_Management_pageHeading;
	@FindBy(xpath = "//a[text()='Achievements']")
	private WebElement College_List_Achievements;
	@FindBy(xpath = "//h2[text()='Achievements']")
	private WebElement College_Achievements_pageHeading;
	@FindBy(xpath = "//a[text()='college council']")
	private WebElement College_List_Collegecouncil;
	@FindBy(xpath = "//a[text()='college committee']")
	private WebElement College_List_collegecommittee;
	@FindBy(xpath = "//a[text()='charity']")
	private WebElement College_List_Charity;
	@FindBy(xpath = "//a[text()='Events']")
	private WebElement College_List_Events;
	@FindBy(xpath = "//a[text()='Videos']")
	private WebElement College_List_Videos;
	@FindBy(xpath = "//h2[text()='Videos']")
	private WebElement College_Videos_pageHeading;
	@FindBy(xpath = "//a[text()='UG Course']")
	private WebElement Course_UGCourse;
	@FindBy(xpath = "//a[text()='B.C.A']")
	private WebElement Course_UGlist_BCA;
	@FindBy(xpath = "//h2[text()='Computer Applications (BCA)']")
	private WebElement UG_BCA_pageHeading;	
	@FindBy(xpath = "//a[text()='B.Com (CA)']")
	private WebElement Course_UGlist_BComCA;
	@FindBy(xpath = "//h2[text()='COMMERCE WITH COMPUTER APPLICATIONS']")
	private WebElement UG_BComCA_pageHeading;
	@FindBy(xpath = "//a[text()='B.Com (Professional Accounting)']")
	private WebElement Course_UGlist_BComPA;
	@FindBy(xpath = "//h2[text()='Bcom Professional Accounting (B.Com(PA))']")
	private WebElement UG_BComPA_pageHeading;
	@FindBy(xpath = "//a[text()='B.Sc Computer Science']")
	private WebElement Course_UGlist_BscCS;
	@FindBy(xpath = "//h2[text()='COMPUTER SCIENCE (B.SC)']")
	private WebElement UG_BscCS_pageHeading;
	@FindBy(xpath = "//a[text()='B.Sc Information Technology']")
	private WebElement Course_UGlist_BscIT;
	@FindBy(xpath = "//h2[text()='INFORMATION TECHNOLOGY (B.SC)']")
	private WebElement UG_BscIT_pageHeading;
	@FindBy(xpath = "//a[text()='B.Com']")
	private WebElement Course_UGlist_Bcom;
	@FindBy(xpath = "//h2[text()='Commerce(B.Com)']")
	private WebElement UG_Bcom_pageHeading;
	@FindBy(xpath = "//a[text()='B.Sc Biotechnology']")
	private WebElement Course_UGlist_BscBiotechnology;
	@FindBy(xpath = "//h2[text()='BIOTECHNOLOGY (B.SC)']")
	private WebElement UG_BscBiotechnology_pageHeading;
	@FindBy(xpath = "//a[text()='B.Sc Catering Science & Hotel Management']")
	private WebElement Course_UGlist_BscCSHM;
	@FindBy(xpath = "//h2[text()='Catering Science Hotel Management']")
	private WebElement UG_BscCSHM_pageHeading;
	@FindBy(xpath = "//a[text()='B.Sc Electronics & Communication Systems']")
	private WebElement Course_UGlist_BscEcs;
	@FindBy(xpath = "//h2[text()='ELECTRONICS AND COMMUNICATION ']")
	private WebElement UG_BscEcs_pageHeading;
	@FindBy(xpath = "//a[text()='B.Sc Mathematics']")
	private WebElement Course_UGlist_BScMathematics;
	@FindBy(xpath = "//h2[text()='MATHEMATICS (B.SC)']")
	private WebElement UG_BScMathematics_pageHeading;
	@FindBy(xpath = "//a[text()='B.A English Literature']")
	private WebElement Course_UGlist_BAEL;
	@FindBy(xpath = "//h2[text()='ENGLISH LITERATURE (B.A)']")
	private WebElement UG_BAEL_pageHeading;
	@FindBy(xpath = "//a[text()='B.B.A (CA)']")
	private WebElement Course_UGlist_BBACA;
	@FindBy(xpath = "//h2[text()='BACHELOR OF BUSINESS ADMINISTRATION (CA)']")
	private WebElement UG_BBACA_pageHeading;
	@FindBy(xpath = "//a[text()='B.Sc Psychology']")
	private WebElement Course_UGlist_BScPsychology;
	@FindBy(xpath = "//h2[text()='COMMERCE WITH COMPUTER APPLICATIONS']")
	private WebElement UG_BScPsychology_pageHeading;
	@FindBy(xpath = "//a[text()='Campus']")
	private WebElement Campus_Campus;
	@FindBy(xpath = "(//ul[@class='sub-menu'])[3]/li/a")
	private WebElement Campus_Campus_pageHeading;
	@FindBy(xpath = "//a[text()='NSS']")
	private WebElement Campus_Nss;
	@FindBy(xpath = "//center[text()='NSS PROGRAMME OFFICER']")
	private WebElement Campus_Nss_pageHeading;
	@FindBy(xpath = "//h2[text()='Gallery']")
	private WebElement Gallery_Pageheading;
	@FindBy(id = "page-banner")
	private WebElement Facilities_pageHeading;	
	@FindBy(xpath = "//a[text()='placement cell']")
	private WebElement placement_placementCell;
	@FindBy(xpath = "//h2[text()='PLACEMENT AND TRAINING CELL']")
	private WebElement placement_placementCell_pageHeading;
	@FindBy(xpath = "//a[text()='Placement Office']")
	private WebElement placement_PO;
	@FindBy(xpath = "//h2[text()='Placement Office']")
	private WebElement placement_PO_pageHeading;
	@FindBy(xpath = "//a[text()='Activities']")
	private WebElement placement_Activities;
	@FindBy(xpath = "//h2[text()='Activities']")
	private WebElement placement_Activities_pageHeading;
	@FindBy(xpath = "//a[text()='companies']")
	private WebElement placement_Companies;
	@FindBy(xpath = "//h2[text()='Companies']")
	private WebElement placement_Companies_pageHeading;
	@FindBy(xpath = "//a[text()='career']")
	private WebElement placement_Career;
	@FindBy(xpath = "//h2[text()='Career']")
	private WebElement placement_Career_pageHeading;	
	@FindBy(xpath = "//a[text()='scholarships']")
	private WebElement Service_Scholarships;
	@FindBy(xpath = "//h2[text()='Scholarships']")
	private WebElement Service_Scholarships_pageHeading;
	@FindBy(xpath = "//a[text()='Prof.Subbiah Yoga Centre']")
	private WebElement Service_PSYC;
	@FindBy(xpath = "//h2[text()='Subbiah Yoga Center']")
	private WebElement Service_PSYC_pageHeading;
	@FindBy(xpath = "//a[text()='Group Insurance']")
	private WebElement Service_GroupInsurance;
	@FindBy(xpath = "//h2[text()='Group Insurance']")
	private WebElement Service_GroupInsurance_pageHeading;
	@FindBy(xpath = "//a[text()='Research Programme']")
	private WebElement Service_RP;
	@FindBy(xpath = "//h2[text()='RESEARCH PROGRAMME']")
	private WebElement Service_RP_pageHeading;
	@FindBy(xpath = "//a[text()='UOW ']")
	private WebElement Service_UOW;
	@FindBy(xpath = "//h2[text()='UOW']")
	private WebElement Service_UOW_pageHeading;	
	@FindBy(xpath = "//a[text()='NIRF']")
	private WebElement NIRF_NIRF;
	@FindBy(xpath = "(//a[text()='NIRF'])[2]")
	private WebElement NIRF_NIRF_pageHeading;
	@FindBy(xpath = "//h2[text()='Contact']")
	private WebElement Contact_pageHeading;
	@FindBy(xpath = "//h2[text()='Campus']")
	private WebElement Donation_pageHeading;

	
	
	public Elements(WebDriver driver) {
		PageFactory.initElements(driver, this);
	}

	public WebElement getCollegeLogo() {
		return CollegeLogo;
	}

	public WebElement getCollegeMailID() {
		return CollegeMailID;
	}

	public WebElement getCollegeContactNumber() {
		return CollegeContactNumber;
	}

	public WebElement getFacebookLink_btn() {
		return FacebookLink_btn;
	}

	public WebElement getYoutubeLink_btn() {
		return YoutubeLink_btn;
	}

	public WebElement getInstagramLink_btn() {
		return InstagramLink_btn;
	}

	public WebElement getStaffLogin_btn() {
		return StaffLogin_btn;
	}

	public WebElement getStudentLogin_btn() {
		return StudentLogin_btn;
	}

	public WebElement getAlumni_btn() {
		return Alumni_btn;
	}

	public WebElement getNav_Home_btn() {
		return Nav_Home_btn;
	}

	public WebElement getNav_College_btn() {
		return Nav_College_btn;
	}

	public WebElement getNav_Course_btn() {
		return Nav_Course_btn;
	}

	public WebElement getNav_Gallery_btn() {
		return Nav_Gallery_btn;
	}

	public WebElement getNav_Facilities_btn() {
		return Nav_Facilities_btn;
	}

	public WebElement getNav_Campus_btn() {
		return Nav_Campus_btn;
	}

	public WebElement getNav_Placement_btn() {
		return Nav_Placement_btn;
	}

	public WebElement getNav_Service_btn() {
		return Nav_Service_btn;
	}

	public WebElement getNav_Nirf_btn() {
		return Nav_Nirf_btn;
	}

	public WebElement getNav_Contact_btn() {
		return Nav_Contact_btn;
	}

	public WebElement getNav_OnlinePayment_btn() {
		return Nav_OnlinePayment_btn;
	}

	public WebElement getNav_Donation_btn() {
		return Nav_Donation_btn;
	}

	public WebElement getNav_College_btnSubmenu() {
		return Nav_College_btnSubmenu;
	}

	public WebElement getNav_Course_btnSubmenu() {
		return Nav_Course_btnSubmenu;
	}

	public WebElement getNav_Campus_btnSubmenu() {
		return Nav_Campus_btnSubmenu;
	}

	public WebElement getNav_Placement_btnSubmenu() {
		return Nav_Placement_btnSubmenu;
	}

	public WebElement getNav_Service_btnSubmenu() {
		return Nav_Service_btnSubmenu;
	}

	public WebElement getNav_Nirf_btnSubmenu() {
		return Nav_Nirf_btnSubmenu;
	}

	public WebElement getStaffLogin_username() {
		return StaffLogin_username;
	}

	public WebElement getStaffLogin_Password() {
		return StaffLogin_Password;
	}

	public WebElement getStaffLogin_Checkbox() {
		return StaffLogin_Checkbox;
	}
	public WebElement getStaffLogin_RememberMe() {
		return StaffLogin_RememberMe;
	}

	public WebElement getStaffLogin_SignIn_btn() {
		return StaffLogin_SignIn_btn;
	}

	public WebElement getStaffLogin_ErrorMessage() {
		return StaffLogin_ErrorMessage;
	}

	public WebElement getAlumni_pageHeading() {
		return Alumni_pageHeading;
	}

	public WebElement getAlumni_Registration_btn() {
		return Alumni_Registration_btn;
	}

	public WebElement getCollege_List_AboutKSG() {
		return College_List_AboutKSG;
	}

	public WebElement getCollege_List_Management() {
		return College_List_Management;
	}

	public WebElement getCollege_Management_pageHeading() {
		return College_Management_pageHeading;
	}

	public WebElement getCollege_List_Achievements() {
		return College_List_Achievements;
	}

	public WebElement getCollege_Achievements_pageHeading() {
		return College_Achievements_pageHeading;
	}

	public WebElement getCollege_List_Collegecouncil() {
		return College_List_Collegecouncil;
	}

	public WebElement getCollege_List_collegecommittee() {
		return College_List_collegecommittee;
	}

	public WebElement getCollege_List_Charity() {
		return College_List_Charity;
	}

	public WebElement getCollege_List_Events() {
		return College_List_Events;
	}

	public WebElement getCollege_List_Videos() {
		return College_List_Videos;
	}

	public WebElement getCollege_Videos_pageHeading() {
		return College_Videos_pageHeading;
	}

	public WebElement getCourse_UGCourse() {
		return Course_UGCourse;
	}

	public WebElement getCourse_UGlist_BCA() {
		return Course_UGlist_BCA;
	}

	public WebElement getUG_BCA_pageHeading() {
		return UG_BCA_pageHeading;
	}

	public WebElement getCourse_UGlist_BComCA() {
		return Course_UGlist_BComCA;
	}

	public WebElement getUG_BComCA_pageHeading() {
		return UG_BComCA_pageHeading;
	}

	public WebElement getCourse_UGlist_BComPA() {
		return Course_UGlist_BComPA;
	}

	public WebElement getUG_BComPA_pageHeading() {
		return UG_BComPA_pageHeading;
	}

	public WebElement getCourse_UGlist_BscCS() {
		return Course_UGlist_BscCS;
	}

	public WebElement getUG_BscCS_pageHeading() {
		return UG_BscCS_pageHeading;
	}

	public WebElement getCourse_UGlist_BscIT() {
		return Course_UGlist_BscIT;
	}

	public WebElement getUG_BscIT_pageHeading() {
		return UG_BscIT_pageHeading;
	}

	public WebElement getCourse_UGlist_Bcom() {
		return Course_UGlist_Bcom;
	}

	public WebElement getUG_Bcom_pageHeading() {
		return UG_Bcom_pageHeading;
	}

	public WebElement getCourse_UGlist_BscBiotechnology() {
		return Course_UGlist_BscBiotechnology;
	}

	public WebElement getUG_BscBiotechnology_pageHeading() {
		return UG_BscBiotechnology_pageHeading;
	}

	public WebElement getCourse_UGlist_BscCSHM() {
		return Course_UGlist_BscCSHM;
	}

	public WebElement getUG_BscCSHM_pageHeading() {
		return UG_BscCSHM_pageHeading;
	}

	public WebElement getCourse_UGlist_BscEcs() {
		return Course_UGlist_BscEcs;
	}

	public WebElement getUG_BscEcs_pageHeading() {
		return UG_BscEcs_pageHeading;
	}

	public WebElement getCourse_UGlist_BScMathematics() {
		return Course_UGlist_BScMathematics;
	}

	public WebElement getUG_BScMathematics_pageHeading() {
		return UG_BScMathematics_pageHeading;
	}

	public WebElement getCourse_UGlist_BAEL() {
		return Course_UGlist_BAEL;
	}

	public WebElement getUG_BAEL_pageHeading() {
		return UG_BAEL_pageHeading;
	}

	public WebElement getCourse_UGlist_BBACA() {
		return Course_UGlist_BBACA;
	}

	public WebElement getUG_BBACA_pageHeading() {
		return UG_BBACA_pageHeading;
	}

	public WebElement getCourse_UGlist_BScPsychology() {
		return Course_UGlist_BScPsychology;
	}

	public WebElement getUG_BScPsychology_pageHeading() {
		return UG_BScPsychology_pageHeading;
	}

	public WebElement getCampus_Campus() {
		return Campus_Campus;
	}

	public WebElement getCampus_Campus_pageHeading() {
		return Campus_Campus_pageHeading;
	}

	public WebElement getCampus_Nss() {
		return Campus_Nss;
	}

	public WebElement getCampus_Nss_pageHeading() {
		return Campus_Nss_pageHeading;
	}

	public WebElement getGallery_Pageheading() {
		return Gallery_Pageheading;
	}

	public WebElement getFacilities_pageHeading() {
		return Facilities_pageHeading;
	}

	public WebElement getPlacement_placementCell() {
		return placement_placementCell;
	}

	public WebElement getPlacement_placementCell_pageHeading() {
		return placement_placementCell_pageHeading;
	}

	public WebElement getPlacement_PO() {
		return placement_PO;
	}

	public WebElement getPlacement_PO_pageHeading() {
		return placement_PO_pageHeading;
	}

	public WebElement getPlacement_Activities() {
		return placement_Activities;
	}

	public WebElement getPlacement_Activities_pageHeading() {
		return placement_Activities_pageHeading;
	}

	public WebElement getPlacement_Companies() {
		return placement_Companies;
	}

	public WebElement getPlacement_Companies_pageHeading() {
		return placement_Companies_pageHeading;
	}

	public WebElement getPlacement_Career() {
		return placement_Career;
	}

	public WebElement getPlacement_Career_pageHeading() {
		return placement_Career_pageHeading;
	}

	public WebElement getService_Scholarships() {
		return Service_Scholarships;
	}

	public WebElement getService_Scholarships_pageHeading() {
		return Service_Scholarships_pageHeading;
	}

	public WebElement getService_PSYC() {
		return Service_PSYC;
	}

	public WebElement getService_PSYC_pageHeading() {
		return Service_PSYC_pageHeading;
	}

	public WebElement getService_GroupInsurance() {
		return Service_GroupInsurance;
	}

	public WebElement getService_GroupInsurance_pageHeading() {
		return Service_GroupInsurance_pageHeading;
	}

	public WebElement getService_RP() {
		return Service_RP;
	}

	public WebElement getService_RP_pageHeading() {
		return Service_RP_pageHeading;
	}

	public WebElement getService_UOW() {
		return Service_UOW;
	}

	public WebElement getService_UOW_pageHeading() {
		return Service_UOW_pageHeading;
	}

	public WebElement getNIRF_NIRF() {
		return NIRF_NIRF;
	}

	public WebElement getNIRF_NIRF_pageHeading() {
		return NIRF_NIRF_pageHeading;
	}

	public WebElement getContact_pageHeading() {
		return Contact_pageHeading;
	}

	public WebElement getDonation_pageHeading() {
		return Donation_pageHeading;
	}
}


# 2.MAIN TEST CLASS
=========================================================================================================================


package package1;

import java.time.Duration;

import org.openqa.selenium.WebDriver;
import org.openqa.selenium.WebDriver.Navigation;
import org.openqa.selenium.firefox.FirefoxDriver;
import org.openqa.selenium.interactions.Actions;
import org.openqa.selenium.support.ui.Select;
import org.testng.annotations.AfterTest;
import org.testng.annotations.BeforeTest;
import org.testng.annotations.Test;
import org.testng.asserts.SoftAssert;

import io.github.bonigarcia.wdm.WebDriverManager;

public class TestMain {

	WebDriver driver;
	Elements po;
	SoftAssert softassert;
	Actions act;
	Navigation nav;
	@BeforeTest
	public void LaunchBrowser() {
		WebDriverManager.chromedriver().setup();
		driver = new FirefoxDriver();
		driver. manage().timeouts().implicitlyWait(Duration.ofSeconds(10));
		driver.manage().window().maximize();
		driver. get("https://www.ksgcollege.com/");
		po = new Elements(driver);
		softassert = new SoftAssert();
		act = new Actions(driver);
		nav = driver.navigate();
	}
	@Test(priority = 1)			//verify the page title
	public void Title() {
		String actualTitle = driver.getTitle();
		String expectedTitle = "K.S.G College of Arts and Science | Best Arts & Science College in Coimbatore";
		softassert.assertEquals(actualTitle, expectedTitle, "Page Title Mismatched");
	}
	@Test(priority = 2)
	public void URL() {			//verify that URL of the main page
		String actualURL = driver.getCurrentUrl();
		String expectedURL = "https://www.ksgcollege.com/";
		softassert.assertEquals(actualURL, expectedURL);
	}	
	@Test(priority = 3)			//verify that college logo is displayed correctly
	public void College_Logo() {
		boolean displayStatus = po.getCollegeLogo().isDisplayed();
		softassert.assertEquals(displayStatus, true,"College Logo is not displayed");
		boolean enableStatus = po.getCollegeLogo().isEnabled();
		softassert.assertEquals(enableStatus, true,"College Logo is not enabled");
	}
	@Test(priority = 4)		//verify that college mail ID is displayed correctly
	public void College_MailID() {
		boolean displayStatus = po.getCollegeMailID().isDisplayed();
		softassert.assertEquals(displayStatus, true, "College MailID is not displayed");
	}
	@Test(priority = 5)		//verify that college contact number is displayed correctly
	public void College_contactNumber() {
		boolean displayStatus = po.getCollegeContactNumber().isDisplayed();
		softassert.assertEquals(displayStatus, true,"College contact number is not displayed");
	}
	@Test(priority = 6)		//Verify the display and enable status of the Facebook button
	public void Facebook_btn() {
		boolean displayStatus = po.getFacebookLink_btn().isDisplayed();
		softassert.assertEquals(displayStatus, true,"Facebook button is not displayed");
		boolean enableStatus = po.getFacebookLink_btn().isEnabled();
		softassert.assertEquals(enableStatus, true,"Facebook button is not enabled");
	}
	@Test(priority = 7)		//Verify the display and enable status of the Youtube button
	public void Youtube_btn() {
		boolean displayStatus = po.getYoutubeLink_btn().isDisplayed();
		softassert.assertEquals(displayStatus, true,"Youtube button is not displayed");
		boolean enableStatus = po.getYoutubeLink_btn().isEnabled();
		softassert.assertEquals(enableStatus, true,"Youtube button is not enabled");
	}
	@Test(priority = 8)		//Verify the display and enable status of the Instagram button
	public void Instagram_btn() {
		boolean displayStatus = po.getInstagramLink_btn().isDisplayed();
		softassert.assertEquals(displayStatus, true,"Instagram button is not displayed");
		boolean enableStatus = po.getInstagramLink_btn().isEnabled();
		softassert.assertEquals(enableStatus, true,"Instagram button is not enabled");
	}
	@Test(priority = 9)		//Verify the display and enable status of the  button
	public void StaffLogin_btn() {
		boolean displayStatus = po.getStaffLogin_btn().isDisplayed();
		softassert.assertEquals(displayStatus, true,"Staff Login button is not displayed");
		boolean enableStatus = po.getStaffLogin_btn().isEnabled();
		softassert.assertEquals(enableStatus, true,"Staff Login button is not enabled");
	}
	@Test(priority = 10)		//Verify the display and enable status of the  button
	public void StudentLogin_btn() {
		boolean displayStatus = po.getStudentLogin_btn().isDisplayed();
		softassert.assertEquals(displayStatus, true,"Student Login button is not displayed");
		boolean enableStatus = po.getStudentLogin_btn().isEnabled();
		softassert.assertEquals(enableStatus, true,"Student Login button is not enabled");
	}
	@Test(priority = 11)		//Verify the display and enable status of the Alumni button
	public void Alumni_btn() {
		boolean displayStatus = po.getAlumni_btn().isDisplayed();
		softassert.assertEquals(displayStatus, true,"Alumni button is not displayed");
		boolean enableStatus = po.getAlumni_btn().isEnabled();
		softassert.assertEquals(enableStatus, true,"Alumni button is not enabled");
	}
	@Test(priority = 12)		//Verify the display and enable status of the HOME button in the navigation bar
	public void Nav_HOME_btn() {
		boolean displayStatus = po.getNav_Home_btn().isDisplayed();
		softassert.assertEquals(displayStatus, true,"HOME button is not displayed in the navigation bar");
		boolean enableStatus = po.getNav_Home_btn().isEnabled();
		softassert.assertEquals(enableStatus, true,"HOME button is not enabled in the navigation bar");
	}
	@Test(priority = 13)		//Verify the display and enable status of the COLLEGE button in the navigation bar
	public void Nav_COLLEGE_btn() {
		boolean displayStatus = po.getNav_College_btn().isDisplayed();
		softassert.assertEquals(displayStatus, true,"COLLEGE button is not displayed in the navigation bar");
		boolean enableStatus = po.getNav_College_btn().isEnabled();
		softassert.assertEquals(enableStatus, true,"COLLEGE button is not enabled in the navigation bar");
	}
	@Test(priority = 14)		//Verify the display and enable status of the COURSE button in the navigation bar
	public void Nav_COURSE_btn() {
		boolean displayStatus = po.getNav_Course_btn().isDisplayed();
		softassert.assertEquals(displayStatus, true,"COURSE button is not displayed in the navigation bar");
		boolean enableStatus = po.getNav_Course_btn().isEnabled();
		softassert.assertEquals(enableStatus, true,"COURSE button is not enabled in the navigation bar");
	}
	@Test(priority = 15)		//Verify the display and enable status of the GALLERY button in the navigation bar
	public void Nav_GALLERY_btn() {
		boolean displayStatus = po.getNav_Gallery_btn().isDisplayed();
		softassert.assertEquals(displayStatus, true,"GALLERY button is not displayed in the navigation bar");
		boolean enableStatus = po.getNav_Gallery_btn().isEnabled();
		softassert.assertEquals(enableStatus, true,"GALLERY button is not enabled in the navigation bar");
	}
	@Test(priority = 16)		//Verify the display and enable status of the FACILITIES button in the navigation bar
	public void Nav_FACILITIES_btn() {
		boolean displayStatus = po.getNav_Facilities_btn().isDisplayed();
		softassert.assertEquals(displayStatus, true,"FACILITIES button is not displayed in the navigation bar");
		boolean enableStatus = po.getNav_Facilities_btn().isEnabled();
		softassert.assertEquals(enableStatus, true,"FACILITIES button is not enabled in the navigation bar");
	}
	@Test(priority = 17)		//Verify the display and enable status of the CAMPUS button in the navigation bar
	public void Nav_CAMPUS_btn() {
		boolean displayStatus = po.getNav_Campus_btn().isDisplayed();
		softassert.assertEquals(displayStatus, true,"CAMPUS button is not displayed in the navigation bar");
		boolean enableStatus = po.getNav_Campus_btn().isEnabled();
		softassert.assertEquals(enableStatus, true,"CAMPUS button is not enabled in the navigation bar");
	}
	@Test(priority = 18)		//Verify the display and enable status of the PLACEMENT button in the navigation bar
	public void Nav_PLACEMENT_btn() {
		boolean displayStatus = po.getNav_Placement_btn().isDisplayed();
		softassert.assertEquals(displayStatus, true,"PLACEMENT button is not displayed in the navigation bar");
		boolean enableStatus = po.getNav_Placement_btn().isEnabled();
		softassert.assertEquals(enableStatus, true,"PLACEMENT button is not enabled in the navigation bar");
	}
	@Test(priority = 19)		//Verify the display and enable status of the SERVICE button in the navigation bar
	public void Nav_SERVICE_btn() {
		boolean displayStatus = po.getNav_Service_btn().isDisplayed();
		softassert.assertEquals(displayStatus, true,"SERVICE button is not displayed in the navigation bar");
		boolean enableStatus = po.getNav_Service_btn().isEnabled();
		softassert.assertEquals(enableStatus, true,"SERVICE button is not enabled in the navigation bar");
	}
	@Test(priority = 20)		//Verify the display and enable status of the NIRF button in the navigation bar
	public void Nav_NIRF_btn() {
		boolean displayStatus = po.getNav_Nirf_btn().isDisplayed();
		softassert.assertEquals(displayStatus, true,"NIRF button is not displayed in the navigation bar");
		boolean enableStatus = po.getNav_Nirf_btn().isEnabled();
		softassert.assertEquals(enableStatus, true,"NIRF button is not enabled in the navigation bar");
	}
	@Test(priority = 21)		//Verify the display and enable status of the CONTACT button in the navigation bar
	public void Nav_CONTACT_btn() {
		boolean displayStatus = po.getNav_Contact_btn().isDisplayed();
		softassert.assertEquals(displayStatus, true,"CONTACT button is not displayed in the navigation bar");
		boolean enableStatus = po.getNav_Contact_btn().isEnabled();
		softassert.assertEquals(enableStatus, true,"CONTACT button is not enabled in the navigation bar");
	}
	@Test(priority = 22)		//Verify the display and enable status of the ONLINE PAYMENT button in the navigation bar
	public void Nav_ONLINEPAYMENT_btn() {
		boolean displayStatus = po.getNav_OnlinePayment_btn().isDisplayed();
		softassert.assertEquals(displayStatus, true,"ONLINE PAYMENT button is not displayed in the navigation bar");
		boolean enableStatus = po.getNav_OnlinePayment_btn().isEnabled();
		softassert.assertEquals(enableStatus, true,"ONLINE PAYMENT button is not enabled in the navigation bar");
	}
	@Test(priority = 23)		//Verify the display and enable status of the DONATION button in the navigation bar
	public void Nav_DONATION_btn() {
		boolean displayStatus = po.getNav_Donation_btn().isDisplayed();
		softassert.assertEquals(displayStatus, true,"DONATION button is not displayed in the navigation bar");
		boolean enableStatus = po.getNav_Donation_btn().isEnabled();
		softassert.assertEquals(enableStatus, true,"DONATION button is not enabled in the navigation bar");
	}
	@Test(priority = 24)		//Verify the text color of the HOME button in the navigation bar
	public void Nav_Home_btn_TextColour() {
		String actualTextColour=po.getNav_Home_btn().getCssValue("color");
		String expectedTextColour="rgb(7, 41, 77)";
		softassert.assertEquals(actualTextColour, expectedTextColour, "HOME button text colour mismatched in the navigation bar");
	}
	@Test(priority = 25)		//Verify the text color of the COLLEGE button in the navigation bar
	public void Nav_COLLEGE_btn_TextColour() throws Exception {
		Thread.sleep(500);
		String actualTextColour=po.getNav_College_btn().getCssValue("color");
		String expectedTextColour="rgb(7, 41, 77)";
		softassert.assertEquals(actualTextColour, expectedTextColour, "COLLEGE button text colour mismatched in the navigation bar");
	}
	@Test(priority = 26)		//Verify the text color of the COURSE button in the navigation bar
	public void Nav_COURSE_btn_TextColour() {
		String actualTextColour=po.getNav_Course_btn().getCssValue("color");
		String expectedTextColour="rgb(7, 41, 77)";
		softassert.assertEquals(actualTextColour, expectedTextColour, "COURSE button text colour mismatched in the navigation bar");
	}
	@Test(priority = 27)		//Verify the text color of the GALLERY button in the navigation bar
	public void Nav_GALLERY_btn_TextColour() {
		String actualTextColour=po.getNav_Gallery_btn().getCssValue("color");
		String expectedTextColour="rgb(7, 41, 77)";
		softassert.assertEquals(actualTextColour, expectedTextColour, "GALLERY button text colour mismatched in the navigation bar");
	}
	@Test(priority = 28)		//Verify the text color of the FACILITIES button in the navigation bar
	public void Nav_FACILITIES_btn_TextColour() {
		String actualTextColour=po.getNav_Facilities_btn().getCssValue("color");
		String expectedTextColour="rgb(7, 41, 77)";
		softassert.assertEquals(actualTextColour, expectedTextColour, "FACILITIES button text colour mismatched in the navigation bar");
	}
	@Test(priority = 29)		//Verify the text color of the CAMPUS button in the navigation bar
	public void Nav_CAMPUS_btn_TextColour() {
		String actualTextColour=po.getNav_Campus_btn().getCssValue("color");
		String expectedTextColour="rgb(7, 41, 77)";
		softassert.assertEquals(actualTextColour, expectedTextColour, "CAMPUS button text colour mismatched in the navigation bar");
	}
	@Test(priority = 30)		//Verify the text color of the PLACEMENT button in the navigation bar
	public void Nav_PLACEMENT_btn_TextColour() {
		String actualTextColour=po.getNav_Placement_btn().getCssValue("color");
		String expectedTextColour="rgb(7, 41, 77)";
		softassert.assertEquals(actualTextColour, expectedTextColour, "PLACEMENT button text colour mismatched in the navigation bar");
	}
	@Test(priority = 31)		//Verify the text color of the SERVICE button in the navigation bar
	public void Nav_SERVICE_btn_TextColour() {
		String actualTextColour=po.getNav_Service_btn().getCssValue("color");
		String expectedTextColour="rgb(7, 41, 77)";
		softassert.assertEquals(actualTextColour, expectedTextColour, "SERVICE button text colour mismatched in the navigation bar");
	}
	@Test(priority = 32)		//Verify the text color of the NIRF button in the navigation bar
	public void Nav_NIRF_btn_TextColour() {
		String actualTextColour=po.getNav_Nirf_btn().getCssValue("color");
		String expectedTextColour="rgb(7, 41, 77)";
		softassert.assertEquals(actualTextColour, expectedTextColour, "NIRF button text colour mismatched in the navigation bar");
	}
	@Test(priority = 33)		//Verify the text color of the CONTACT button in the navigation bar
	public void Nav_CONTACT_btn_TextColour() {
		String actualTextColour=po.getNav_Contact_btn().getCssValue("color");
		String expectedTextColour="rgb(7, 41, 77)";
		softassert.assertEquals(actualTextColour, expectedTextColour, "CONTACT button text colour mismatched in the navigation bar");
	}
	@Test(priority = 34)		//Verify the text color of the ONLINE PAYMENT button in the navigation bar
	public void Nav_ONLINEPAYMENT_btn_TextColour() {
		String actualTextColour=po.getNav_OnlinePayment_btn().getCssValue("color");
		String expectedTextColour="rgb(7, 41, 77)";
		softassert.assertEquals(actualTextColour, expectedTextColour, "ONLINE PAYMENT button text colour mismatched in the navigation bar");
	}
	@Test(priority = 35)		//Verify the text color of the DONATION button in the navigation bar
	public void Nav_DONATION_btn_TextColour() {
		String actualTextColour=po.getNav_Donation_btn().getCssValue("color");
		String expectedTextColour="rgb(179, 0, 40)";
		softassert.assertEquals(actualTextColour, expectedTextColour, "DONATION button text colour mismatched in the navigation bar");
	}
	@Test(priority = 36)		//Verify the text color of the HOME button in the navigation bar after hovering
	public void Nav_HOME_btn_HoverTextColour() throws Exception {
		act.moveToElement(po.getNav_Home_btn()).perform();
		Thread.sleep(500);
		String actualTextColour=po.getNav_Home_btn().getCssValue("color");
		String expectedTextColour="rgb(255, 255, 255)";
		softassert.assertEquals(actualTextColour, expectedTextColour, "HOME button text colour mismatched in the navigation bar after hovering");
	}
	@Test(priority = 37)		//Verify the text color of the COLLEGE button in the navigation bar after hovering
	public void Nav_COLLEGE_btn_HoverTextColour() throws Exception {
		act.moveToElement(po.getNav_College_btn()).perform();
		Thread.sleep(500);
		String actualTextColour=po.getNav_College_btn().getCssValue("color");
		String expectedTextColour="rgb(255, 255, 255)";
		softassert.assertEquals(actualTextColour, expectedTextColour, "COLLEGE button text colour mismatched in the navigation bar after hovering");
	}
	@Test(priority = 38)		//Verify the text color of the COURSE button in the navigation bar after hovering
	public void Nav_COURSE_btn_HoverTextColour() throws Exception {
		act.moveToElement(po.getNav_Course_btn()).perform();
		Thread.sleep(500);
		String actualTextColour=po.getNav_Course_btn().getCssValue("color");
		String expectedTextColour="rgb(255, 255, 255)";
		softassert.assertEquals(actualTextColour, expectedTextColour, "COURSE button text colour mismatched in the navigation bar after hovering");
	}
	@Test(priority = 39)		//Verify the text color of the GALLERY button in the navigation bar after hovering
	public void Nav_GALLERY_btn_HoverTextColour() throws Exception {
		act.moveToElement(po.getNav_Gallery_btn()).perform();
		Thread.sleep(500);
		String actualTextColour=po.getNav_Gallery_btn().getCssValue("color");
		String expectedTextColour="rgb(255, 255, 255)";
		softassert.assertEquals(actualTextColour, expectedTextColour, "GALLERY button text colour mismatched in the navigation bar after hovering");
	}
	@Test(priority = 40)		//Verify the text color of the FACILITIES button in the navigation bar after hovering
	public void Nav_FACILITIES_btn_HoverTextColour() throws Exception {
		act.moveToElement(po.getNav_Facilities_btn()).perform();
		Thread.sleep(500);
		String actualTextColour=po.getNav_Facilities_btn().getCssValue("color");
		String expectedTextColour="rgb(255, 255, 255)";
		softassert.assertEquals(actualTextColour, expectedTextColour, "FACILITIES button text colour mismatched in the navigation bar after hovering");
	}
	@Test(priority = 41)		//Verify the text color of the CAMPUS button in the navigation bar after hovering
	public void Nav_CAMPUS_btn_HoverTextColour() throws Exception {
		act.moveToElement(po.getNav_Campus_btn()).perform();
		Thread.sleep(500);
		String actualTextColour=po.getNav_Campus_btn().getCssValue("color");
		String expectedTextColour="rgb(255, 255, 255)";
		softassert.assertEquals(actualTextColour, expectedTextColour, "CAMPUS button text colour mismatched in the navigation bar after hovering");
	}
	@Test(priority = 42)		//Verify the text color of the PLACEMENT button in the navigation bar after hovering
	public void Nav_PLACEMENT_btn_HoverTextColour() throws Exception {
		act.moveToElement(po.getNav_Placement_btn()).perform();
		Thread.sleep(500);
		String actualTextColour=po.getNav_Placement_btn().getCssValue("color");
		String expectedTextColour="rgb(255, 255, 255)";
		softassert.assertEquals(actualTextColour, expectedTextColour, "PLACEMENT button text colour mismatched in the navigation bar after hovering");
	}
	@Test(priority = 43)		//Verify the text color of the SERVICE button in the navigation bar after hovering
	public void Nav_SERVICE_btn_HoverTextColour() throws Exception {
		act.moveToElement(po.getNav_Service_btn()).perform();
		Thread.sleep(500);
		String actualTextColour=po.getNav_Service_btn().getCssValue("color");
		String expectedTextColour="rgb(255, 255, 255)";
		softassert.assertEquals(actualTextColour, expectedTextColour, "SERVICE button text colour mismatched in the navigation bar after hovering");
	}
	@Test(priority = 44)		//Verify the text color of the NIRF button in the navigation bar after hovering
	public void Nav_NIRF_btn_HoverTextColour() throws Exception {
		act.moveToElement(po.getNav_Nirf_btn()).perform();
		Thread.sleep(500);
		String actualTextColour=po.getNav_Nirf_btn().getCssValue("color");
		String expectedTextColour="rgb(255, 255, 255)";
		softassert.assertEquals(actualTextColour, expectedTextColour, "NIRF button text colour mismatched in the navigation bar after hovering");
	}
	@Test(priority = 45)		//Verify the text color of the CONTACT button in the navigation bar after hovering
	public void Nav_CONTACT_btn_HoverTextColour() throws Exception {
		act.moveToElement(po.getNav_Contact_btn()).perform();
		Thread.sleep(500);
		String actualTextColour=po.getNav_Contact_btn().getCssValue("color");
		String expectedTextColour="rgb(255, 255, 255)";
		softassert.assertEquals(actualTextColour, expectedTextColour, "CONTACT button text colour mismatched in the navigation bar after hovering");
	}
	@Test(priority = 46)		//Verify the text color of the ONLINE PAYMENT button in the navigation bar after hovering
	public void Nav_ONLINEPAYMENT_btn_HoverTextColour() throws Exception {
		act.moveToElement(po.getNav_OnlinePayment_btn()).perform();
		Thread.sleep(500);
		String actualTextColour=po.getNav_OnlinePayment_btn().getCssValue("color");
		String expectedTextColour="rgb(255, 255, 255)";
		softassert.assertEquals(actualTextColour, expectedTextColour, "ONLINE PAYMENT button text colour mismatched in the navigation bar after hovering");
	}
	@Test(priority = 47)		//Verify the text color of the DONATION button in the navigation bar after hovering
	public void Nav_DONATION_btn_HoverTextColour() throws Exception {
		act.moveToElement(po.getNav_Donation_btn()).perform();
		Thread.sleep(500);
		String actualTextColour=po.getNav_Donation_btn().getCssValue("color");
		String expectedTextColour="rgb(255, 255, 255)";
		softassert.assertEquals(actualTextColour, expectedTextColour, "DONATION button text colour mismatched in the navigation bar after hovering");
	}
	@Test(priority = 48)		//Verify that the sub menu of the COLLEGE button is displayed upon hovering
	public void Nav_COLLEGE_btnSubmenu() throws Exception {
		act.moveToElement(po.getNav_College_btn()).perform();
		Thread.sleep(500);
		boolean actualValue= po.getNav_College_btnSubmenu().isDisplayed();
		softassert.assertEquals(actualValue, true, "COLLEGE sub menu is not displayed");
	}
	@Test(priority = 49)		//Verify that the sub menu of the COURSE button is displayed upon hovering
	public void Nav_COURSE_btnSubmenu() {
		act.moveToElement(po.getNav_Course_btn()).perform();
		boolean actualValue= po.getNav_Course_btnSubmenu().isDisplayed();
		softassert.assertEquals(actualValue, true, "COURSE sub menu is not displayed");
	}
	@Test(priority = 50)		//Verify that the sub menu of the CAMPUS button is displayed upon hovering
	public void Nav_CAMPUS_btnSubmenu() {
		act.moveToElement(po.getNav_Campus_btn()).perform();
		boolean actualValue= po.getNav_Campus_btnSubmenu().isDisplayed();
		softassert.assertEquals(actualValue, true, "CAMPUS sub menu is not displayed");
	}
	@Test(priority = 51)		//Verify that the sub menu of the PLACEMENT button is displayed upon hovering
	public void Nav_PLACEMENT_btnSubmenu() {
		act.moveToElement(po.getNav_Placement_btn()).perform();
		boolean actualValue= po.getNav_Placement_btnSubmenu().isDisplayed();
		softassert.assertEquals(actualValue, true, "PLACEMENT sub menu is not displayed");
	}
	@Test(priority = 52)		//Verify that the sub menu of the SERVICE button is displayed upon hovering
	public void Nav_SERVICE_btnSubmenu() {
		act.moveToElement(po.getNav_Service_btn()).perform();
		boolean actualValue= po.getNav_Service_btnSubmenu().isDisplayed();
		softassert.assertEquals(actualValue, true, "SERVICE sub menu is not displayed");
	}
	@Test(priority = 53)		//Verify that the sub menu of the NIRF button is displayed upon hovering
	public void Nav_NIRF_btnSubmenu() {
		act.moveToElement(po.getNav_Nirf_btn()).perform();
		boolean actualValue= po.getNav_Nirf_btnSubmenu().isDisplayed();
		softassert.assertEquals(actualValue, true, "NIRF sub menu is not displayed");
	}
	@Test(priority = 54)		//Verify that the Staff Login page URL
	public void StaffLogin_page() {
		po.getStaffLogin_btn().click();
		String actualURL = driver.getCurrentUrl();
		String expectedURL = "https://www.ksgcollege.com/Smart-ERP/";
		softassert.assertEquals(actualURL, expectedURL, "Staff Login page URL mismatched");
	}
	@Test(priority = 55)		//Verify that Username input box is accepting the data in the Staff Login page
	public void StaffLogin_Username() throws Exception {
		String data="exampleusername@gmail.com";
		po.getStaffLogin_username().sendKeys(data);
		String actualData=po.getStaffLogin_username().getAttribute("value");
		softassert.assertEquals(actualData, data, "Usernaame input box is not working peoperly");
	}
	@Test(priority = 56)		//Verify that Password input box is accepting the data in the Staff Login page
	public void StaffLogin_Password() throws Exception {
		String data="examplePassword@123";
		po.getStaffLogin_Password().sendKeys(data);
		String actualData=po.getStaffLogin_Password().getAttribute("value");
		softassert.assertEquals(actualData, data, "Passord input box is not working peoperly");
	}
	@Test(priority = 57)		//Verify The working of Remember me CheckBox in the Staff Login page
	public void StaffLogin_Checkbox() throws Exception {
		boolean enableStatus = po.getStaffLogin_Checkbox().isSelected();
		softassert.assertEquals(enableStatus, true,"'Remember me' checkbox is not enabled");
		po.getStaffLogin_RememberMe().click();
		Thread.sleep(2000);
		boolean enableStatus1 = po.getStaffLogin_Checkbox().isSelected();
		softassert.assertEquals(enableStatus1, false,"'Remember me' checkbox is not disbled");
	}
	@Test(priority = 58)		//Verify the display and enable status of Sign In button in the Staff Login page
	public void StaffLogin_SignIn() {
		boolean displayStatus = po.getStaffLogin_SignIn_btn().isDisplayed();
		softassert.assertEquals(displayStatus, true,"'SIGN IN' button is not displayed in the Staff Login page");
		boolean enableStatus = po.getStaffLogin_SignIn_btn().isEnabled();
		softassert.assertEquals(enableStatus, true,"'SIGN IN' button is not enabled in the Staff Login page");
	}
	@Test(priority = 59)		//Verify that Error message is displayed while login with invalid credentials
	public void StaffLogin_Login() {
		nav.refresh();
		String username="exampleusername@gmail.com";
		String password="examplePassword@123";
		po.getStaffLogin_username().sendKeys(username);
		po.getStaffLogin_Password().sendKeys(password);
		po.getStaffLogin_SignIn_btn().click();
		boolean displayStatus = po.getStaffLogin_ErrorMessage().isDisplayed();
		softassert.assertEquals(displayStatus, true, "Error message is not displayed");
	}
	@Test(priority = 60)		//Verify that the Alumni page URL
	public void Alumni_page_URL() throws Exception {
		driver. get("https://www.ksgcollege.com/");
		po.getAlumni_btn().click();
		String actualURL = driver.getCurrentUrl();
		String expectedURL = "https://www.ksgcollege.com/Alumni.php";
		softassert.assertEquals(actualURL, expectedURL, "Alumni page URL is mismatched");
	}
	@Test(priority = 61)		//Verify that the Alumni page Heading
	public void Alumni_pageHeading() {
		boolean displayStatus = po.getAlumni_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "Alumni heading is not displayed in the page");
	}
	@Test(priority = 62)		//Verify the Registration button is displayed in the Alumni page
	public void Alumni_RegistrationBtn() {
		boolean displayStatus = po.getAlumni_Registration_btn().isDisplayed();
		softassert.assertEquals(displayStatus, true, "Alumni Registration button is not displayed in the page");
	}
	@AfterTest
	public void CloseBrowser() {
		driver.manage().window().minimize();
		driver.close();
		softassert.assertAll();
	}
}







# 3.SUBMODULES TEST CLASS
=========================================================================================================================


package package1;

import java.time.Duration;

import org.openqa.selenium.WebDriver;
import org.openqa.selenium.WebDriver.Navigation;
import org.openqa.selenium.firefox.FirefoxDriver;
import org.openqa.selenium.interactions.Actions;
import org.testng.annotations.AfterTest;
import org.testng.annotations.BeforeMethod;
import org.testng.annotations.BeforeTest;
import org.testng.annotations.Test;
import org.testng.asserts.SoftAssert;

import io.github.bonigarcia.wdm.WebDriverManager;

public class SubMenuPages {


	WebDriver driver;
	Elements po;
	SoftAssert softassert;
	Actions act;
	Navigation nav;
	@BeforeTest
	public void LaunchBrowser() {
		WebDriverManager.chromedriver().setup();
		driver = new FirefoxDriver();
		driver. manage().timeouts().implicitlyWait(Duration.ofSeconds(10));
		driver.manage().window().maximize();
		driver. get("https://www.ksgcollege.com/");
		po = new Elements(driver);
		softassert = new SoftAssert();
		act = new Actions(driver);
	}
	@BeforeMethod
	public void OpenHomepage() {
		po.getNav_Home_btn().click();
	}
	@Test(priority = 1)		//Verify the AboutKSG page URL
	public void College_List_AboutKSG() {
		act.moveToElement(po.getNav_College_btn()).perform();
		po.getCollege_List_AboutKSG().click();
		String actualURL = driver.getCurrentUrl();
		String expectedURL = "https://www.ksgcollege.com/About.php";
		softassert.assertEquals(actualURL, expectedURL, "About KSG page URL is mismatched");
	}
	@Test(priority = 2)		//Verify the Management page URL and Heading of the page
	public void College_List_Management() throws Exception {
		act.moveToElement(po.getNav_College_btn()).perform();
		Thread.sleep(500);
		po.getCollege_List_Management().click();
		String actualURL = driver.getCurrentUrl();
		String expectedURL = "https://www.ksgcollege.com/Management.php";
		softassert.assertEquals(actualURL, expectedURL, "Management page URL is mismatched");
		boolean displayStatus = po.getCollege_Management_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "Management heading is not displayed");
	}
	@Test(priority = 3)		//Verify the Achievements page URL and Heading of the page
	public void College_List_Achievements() {
		act.moveToElement(po.getNav_College_btn()).perform();
		po.getCollege_List_Achievements().click();
		String actualURL = driver.getCurrentUrl();
		String expectedURL = "https://www.ksgcollege.com/Achivement.php";
		softassert.assertEquals(actualURL, expectedURL, "Achievements page URL is mismatched");
		boolean displayStatus = po.getCollege_Achievements_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "Achievements heading is not displayed");
	}
	@Test(priority = 4)		//Verify the College council page URL
	public void College_List_Collegecouncil() {
		act.moveToElement(po.getNav_College_btn()).perform();
		po.getCollege_List_Collegecouncil().click();
		String actualURL = driver.getCurrentUrl();
		String expectedURL = "https://www.ksgcollege.com/collegecouncil.php";
		softassert.assertEquals(actualURL, expectedURL, "College council page URL is mismatched");
	}
	@Test(priority = 5)		//Verify the College committee page URL
	public void College_List_Collegecommittee() {
		act.moveToElement(po.getNav_College_btn()).perform();
		po.getCollege_List_collegecommittee().click();
		String actualURL = driver.getCurrentUrl();
		String expectedURL = "https://www.ksgcollege.com/collegecommittees.php";
		softassert.assertEquals(actualURL, expectedURL, "College committee page URL is mismatched");
	}
	@Test(priority = 6)		//Verify the Charity page URL
	public void College_List_Charity() {
		act.moveToElement(po.getNav_College_btn()).perform();
		po.getCollege_List_Charity().click();
		String actualURL = driver.getCurrentUrl();
		String expectedURL = "https://www.ksgcollege.com/charity.php";
		softassert.assertEquals(actualURL, expectedURL, "Charity page URL is mismatched");
	}
	@Test(priority = 7)		//Verify the Events page URL
	public void College_List_Events() {
		act.moveToElement(po.getNav_College_btn()).perform();
		po.getCollege_List_Events().click();
		String actualURL = driver.getCurrentUrl();
		String expectedURL = "https://www.ksgcollege.com/events.php";
		softassert.assertEquals(actualURL, expectedURL, "Events page URL is mismatched");
	}
	@Test(priority = 8)		//Verify the Videos page URL and Heading of the page
	public void College_List_Videos() throws Exception {
		act.moveToElement(po.getNav_College_btn()).perform();
		Thread.sleep(500);
		po.getCollege_List_Videos().click();
		String actualURL = driver.getCurrentUrl();
		String expectedURL = "https://www.ksgcollege.com/Video.php";
		softassert.assertEquals(actualURL, expectedURL, "Videos page URL is mismatched");
		boolean displayStatus = po.getCollege_Videos_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "Videos heading is not displayed");
	}
	@Test(priority = 9)		//Verify the BCA page Heading is displayed
	public void UG_BCA() {
		act.moveToElement(po.getNav_Course_btn()).perform();
		act.moveToElement(po.getCourse_UGCourse()).perform();
		po.getCourse_UGlist_BCA().click();
		boolean displayStatus = po.getUG_BCA_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "BCA page heading is not displayed");
	}
	@Test(priority = 10)	//Verify the BCom(CA) page Heading is displayed
	public void UG_BComCA() {
		act.moveToElement(po.getNav_Course_btn()).perform();
		act.moveToElement(po.getCourse_UGCourse()).perform();
		po.getCourse_UGlist_BComCA().click();
		boolean displayStatus = po.getUG_BComCA_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "BCom(CA) page heading is not displayed");
	}
	@Test(priority = 11)	//Verify the B.Com (Professional Accounting) page Heading is displayed
	public void UG_BComPA() {
		act.moveToElement(po.getNav_Course_btn()).perform();
		act.moveToElement(po.getCourse_UGCourse()).perform();
		po.getCourse_UGlist_BComPA().click();
		boolean displayStatus = po.getUG_BComPA_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "B.Com (Professional Accounting) page heading is not displayed");
	}
	@Test(priority = 12)	//Verify the B.Sc Computer Science page Heading is displayed
	public void UG_BscCS() {
		act.moveToElement(po.getNav_Course_btn()).perform();
		act.moveToElement(po.getCourse_UGCourse()).perform();
		po.getCourse_UGlist_BscCS().click();
		boolean displayStatus = po.getUG_BscCS_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "B.Sc Computer Science page heading is not displayed");
	}
	@Test(priority = 13)	//Verify the B.Sc Information Technology page Heading is displayed
	public void UG_BscIT() {
		act.moveToElement(po.getNav_Course_btn()).perform();
		act.moveToElement(po.getCourse_UGCourse()).perform();
		po.getCourse_UGlist_BscIT().click();
		boolean displayStatus = po.getUG_BscIT_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "B.Sc Information Technology page heading is not displayed");
	}
	@Test(priority = 14)	//Verify the B.Com page Heading is displayed
	public void UG_Bcom() {
		act.moveToElement(po.getNav_Course_btn()).perform();
		act.moveToElement(po.getCourse_UGCourse()).perform();
		po.getCourse_UGlist_Bcom().click();
		boolean displayStatus = po.getUG_Bcom_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "B.Com page heading is not displayed");
	}

	@Test(priority = 15)	//Verify the B.Sc Biotechnology page Heading is displayed
	public void UG_BscBiotechnology() {
		act.moveToElement(po.getNav_Course_btn()).perform();
		act.moveToElement(po.getCourse_UGCourse()).perform();
		po.getCourse_UGlist_BscBiotechnology().click();
		boolean displayStatus = po.getUG_BscBiotechnology_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "B.Sc Biotechnology page heading is not displayed");
	}
	@Test(priority = 16)	//Verify the B.Sc Catering Science & Hotel Management page Heading is displayed
	public void UG_BscCSHM() {
		act.moveToElement(po.getNav_Course_btn()).perform();
		act.moveToElement(po.getCourse_UGCourse()).perform();
		po.getCourse_UGlist_BscCSHM().click();
		boolean displayStatus = po.getUG_BscCSHM_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "B.Sc Catering Science & Hotel Management page heading is not displayed");
	}
	@Test(priority = 17)	//Verify the B.Sc Electronics & Communication Systems page Heading is displayed
	public void UG_BscEcs() {
		act.moveToElement(po.getNav_Course_btn()).perform();
		act.moveToElement(po.getCourse_UGCourse()).perform();
		po.getCourse_UGlist_BscEcs().click();
		boolean displayStatus = po.getUG_BscEcs_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "B.Sc Electronics & Communication Systems page heading is not displayed");
	}
	@Test(priority = 18)	//Verify the B.Sc Mathematics page Heading is displayed
	public void UG_BScMathematics() {
		act.moveToElement(po.getNav_Course_btn()).perform();
		act.moveToElement(po.getCourse_UGCourse()).perform();
		po.getCourse_UGlist_BScMathematics().click();
		boolean displayStatus = po.getUG_BScMathematics_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "B.Sc Mathematics page heading is not displayed");
	}
	@Test(priority = 19)	//Verify the B.A English Literature page Heading is displayed
	public void UG_BAEL() {
		act.moveToElement(po.getNav_Course_btn()).perform();
		act.moveToElement(po.getCourse_UGCourse()).perform();
		po.getCourse_UGlist_BAEL().click();
		boolean displayStatus = po.getUG_BAEL_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "B.A English Literature page heading is not displayed");
	}
	@Test(priority = 20)	//Verify the B.B.A (CA) page Heading is displayed
	public void UG_BBACA() {
		act.moveToElement(po.getNav_Course_btn()).perform();
		act.moveToElement(po.getCourse_UGCourse()).perform();
		po.getCourse_UGlist_BBACA().click();
		boolean displayStatus = po.getUG_BBACA_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "B.B.A (CA) page heading is not displayed");
	}
	@Test(priority = 21)	//Verify the B.Sc Psychology page Heading is displayed
	public void UG_BScPsychology() {
		act.moveToElement(po.getNav_Course_btn()).perform();
		act.moveToElement(po.getCourse_UGCourse()).perform();
		po.getCourse_UGlist_BScPsychology().click();
		boolean displayStatus = po.getUG_BScPsychology_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "B.Sc Psychology page heading is not displayed");
	}
	@Test(priority = 22)	//Verify the Campus page Heading is displayed
	public void CAMPUSlist_campus() {
		act.moveToElement(po.getNav_Campus_btn()).perform();
		po.getCampus_Campus().click();
		boolean displayStatus = po.getCampus_Campus_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "Campus page heading is not displayed");
	}
	@Test(priority = 23)	//Verify the NSS page Heading is displayed
	public void CAMPUSlist_NSS() {
		act.moveToElement(po.getNav_Campus_btn()).perform();
		po.getCampus_Nss().click();
		boolean displayStatus = po.getCampus_Nss_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "NSS page heading is not displayed");
	}
	@Test(priority = 24)	//Verify the Gallery page Heading is displayed
	public void GalleryPage() {
		po.getNav_Gallery_btn().click();
		boolean displayStatus = po.getGallery_Pageheading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "Gallery page heading is not displayed");
	}
	@Test(priority = 25)	//Verify the Facilities page Heading is displayed
	public void FacilitiesPage() {
		po.getNav_Facilities_btn().click();
		boolean displayStatus = po.getFacilities_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "Facilities page heading is not displayed");
	}
	@Test(priority = 26)	//Verify the placement cell page Heading is displayed
	public void Placement_placementCell() {
		act.moveToElement(po.getNav_Placement_btn()).perform();
		po.getPlacement_placementCell().click();
		boolean displayStatus = po.getPlacement_placementCell_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "placement cell page heading is not displayed");
	}
	@Test(priority = 27)	//Verify the Placement Office page Heading is displayed
	public void Placement_PlacementPO() {
		act.moveToElement(po.getNav_Placement_btn()).perform();
		po.getPlacement_PO().click();
		boolean displayStatus = po.getPlacement_PO_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "Placement Office page heading is not displayed");
	}
	@Test(priority = 28)	//Verify the Activities page Heading is displayed
	public void Placement_Activities() {
		act.moveToElement(po.getNav_Placement_btn()).perform();
		po.getPlacement_Activities().click();
		boolean displayStatus = po.getPlacement_Activities_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "Activities page heading is not displayed");
	}
	@Test(priority = 29)	//Verify the companies page Heading is displayed
	public void Placement_Companies() throws Exception {
		act.moveToElement(po.getNav_Placement_btn()).perform();
		Thread.sleep(500);
		po.getPlacement_Companies().click();
		boolean displayStatus = po.getPlacement_Companies_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "companies page heading is not displayed");
	}
	@Test(priority = 30)	//Verify the career page Heading is displayed
	public void Placement_Career() {
		act.moveToElement(po.getNav_Placement_btn()).perform();
		po.getPlacement_Career().click();
		boolean displayStatus = po.getPlacement_Career_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "career page heading is not displayed");
	}
	@Test(priority = 31)	//Verify the scholarships page Heading is displayed
	public void Service_Scholarships() {
		act.moveToElement(po.getNav_Service_btn()).perform();
		po.getService_Scholarships().click();
		boolean displayStatus = po.getService_Scholarships_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "scholarships page heading is not displayed");
	}
	@Test(priority = 32)	//Verify the Prof.Subbiah Yoga Centre page Heading is displayed
	public void Service_PSYC() {
		act.moveToElement(po.getNav_Service_btn()).perform();
		po.getService_PSYC().click();
		boolean displayStatus = po.getService_PSYC_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "Prof.Subbiah Yoga Centre page heading is not displayed");
	}
	@Test(priority = 33)	//Verify the Group Insurance page Heading is displayed
	public void Service_GroupInsurance() {
		act.moveToElement(po.getNav_Service_btn()).perform();
		po.getService_GroupInsurance().click();
		boolean displayStatus = po.getService_GroupInsurance_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "Group Insurance page heading is not displayed");
	}
	@Test(priority = 34)	//Verify the Research Programme page Heading is displayed
	public void Service_RP() {
		act.moveToElement(po.getNav_Service_btn()).perform();
		po.getService_RP().click();
		boolean displayStatus = po.getService_RP_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "Research Programme page heading is not displayed");
	}
	@Test(priority = 35)	//Verify the UOW page Heading is displayed
	public void Service_UOW() {
		act.moveToElement(po.getNav_Service_btn()).perform();
		po.getService_UOW().click();
		boolean displayStatus = po.getService_UOW_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "UOW page heading is not displayed");
	}
	@Test(priority = 36)	//Verify the NIRF page Heading is displayed
	public void NIRF_Nirf() {
		act.moveToElement(po.getNav_Nirf_btn()).perform();
		po.getNIRF_NIRF().click();
		boolean displayStatus = po.getNIRF_NIRF_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "NIRF page heading is not displayed");
	}
	@Test(priority = 37)	//Verify the Contact page Heading is displayed
	public void Contact_page() {
		po.getNav_Contact_btn().click();
		boolean displayStatus = po.getContact_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "Contact page heading is not displayed");
	}
	@Test(priority = 38)	//Verify the Donation page Heading is displayed
	public void Donation_page() {
		po.getNav_Donation_btn().click();
		boolean displayStatus = po.getDonation_pageHeading().isDisplayed();
		softassert.assertEquals(displayStatus, true, "Donation page heading is not displayed");
	}
	
	
	
	@AfterTest
	public void CloseBrowser() {
		driver.close();
		softassert.assertAll();
	}
}


# 4.XML PROGRAME FOR BATCH EXECUTION
=========================================================================================================================


<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE suite SYSTEM "https://testng.org/testng-1.0.dtd">
<suite name="Suite">
  <test thread-count="5" name="Test">
    <classes>
      <class name="package1.TestMain"/>
      <class name="package1.SubMenuPages"/>
    </classes>
  </test> <!-- Test -->
</suite> <!-- Suite -->

