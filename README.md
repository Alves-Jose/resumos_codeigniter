# resumos_codeigniter
Minhas anotações durante o aprendizado de CodeIgniter :)


***Controllers:***
Controllers são responsáveis por lidar com as requisições do usuário e coordenar as ações. Eles recebem as requisições, processam os dados, interagem com os modelos e carregam as visualizações apropriadas. 

Exemplo:

class Home extends CI_Controller {
    public function index() {
        // Carregar uma view
        $this->load->view('home_view');
    }
}

***Explicação da public function index():***

Visibilidade ("public"): A palavra-chave "public" é um modificador de acesso que **determina quem pode acessar a função*. Quando uma função é declarada como pública, ela pode ser acessada de qualquer lugar, seja dentro da classe onde está definida ou a partir de outras partes do código que têm acesso à instância dessa classe.

"function": A palavra-chave "function" é usada para declarar que estamos criando uma função ou método. ***Uma função é um bloco de código autônomo que pode receber parâmetros, executar tarefas e retornar valores.***

Nome da função ("index"): "index" é o nome dado a essa função. O nome da função é usado para chamá-la e executar o código contido dentro dela. O nome pode ser escolhido de acordo com o propósito da função, ***mas "index" é frequentemente usado para representar a funcionalidade de exibição ou acesso à página inicial ou ponto de entrada de um sistema, como em aplicações web***

***public function index()*** indica que você está criando uma função pública chamada "index". O que acontece dentro dessa função ***depende do código que você escreve dentro do bloco da função***. No contexto de um aplicativo web, por exemplo, a função "index" poderia ser usada para ***renderizar e exibir a página inicial do site ou aplicativo***.

Exemplo: 
class HomeController {
    public function index() {
        // Código para exibir a página inicial
    }
}

