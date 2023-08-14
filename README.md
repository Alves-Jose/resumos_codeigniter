# resumos_codeigniter
Minhas anotações durante o aprendizado de CodeIgniter :)

**Controllers:**
Controllers são responsáveis por lidar com as requisições do usuário e coordenar as ações. Eles recebem as requisições, processam os dados, interagem com os modelos e carregam as visualizações apropriadas. 

Exemplo:

class Home extends CI_Controller {
    public function index() {
        // Carregar uma view
        $this->load->view('home_view');
    }
}
