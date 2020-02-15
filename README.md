# PDF39e128
Codeigniter Library for Generate Barcode code39 and code128 in FPDF

Installation:

1. Copy this fpdf folder to YOUR_CODEIGNITER/application/third_party/here....
2. Copy Code39e128.php to YOUR_CODEIGNITER/application/library/here....


Usage:
class Test extends CI_Controller {
	public function __construct()
	{
		parent::__construct();
    ........
    .........
		$this->load->library('Code39e128');
	}
