Phalcon深度实践纠正

#P158#
##1.##
>class IndexController extends Controller
改为
class Module implements ModuleDefinitionInterface

##2.##
>public function registerServices(DiInterface $di)
后移四个英文空格
