# Седмица 4 - Циклични оператори

Цикъл
=

Алгоритъм, в който дадена група от действия се изпълнява необходимият брой пъти, докато е изпълнено дадено условие.

Оператор за цикъл for
=

**Общият вид:**

	for (израз1; израз2; израз3) 
  
	{
  
		оператор;
    
	}
  
където: 

**израз1** служи за инициализация (начално задаване) на индекса на цикъла (или и на други променливи) и се изпълнява веднъж – при влизане в цикъла.

**израз2** е проверка на условието за излизане от цикъла и се пресмята преди всяко преминаване през тялото на цикъла.

**израз3** е актуализация на параметрите на цикъла и се пресмята след всяко изпълнение на оператора в тялото на цикъла.

Тялото на цикъла е означено с оператор, който може да е единствен оператор или в тялото да има много оператори.

Цикълът продължава докато **израз2** стане **0** (false), при което управлението се предава на оператора, следващ непосредствено тялото на **for**.

***Възможно е цикълът да не се изпълни нито веднъж.***

Някои от изразите в отделните секции на оператор for могат да отсъстват като стойността им се приема за различна от 0 (true).


Оператор за цикъл с предусловие – while
=

**Общият вид:**

	while (израз)
  
	{
  
		оператор;
    
	}
  
Операторът се изпълнява многократно докато израз има стойност различна от **0** (true). Ако израз има стойност **0** (false), изпълнението на цикъла се преустановява.

***Стойността на израза се изчислява преди изпълнението на оператора и е възможно тялото на цикъла да не бъде изпълнено нито веднъж.***


Оператор за цикъл с постусловие - do…while
=

**Общият вид:**

	do	
  
  	{
  
		 оператор;
     
	} while (израз);
  
Изпълнява се операторът (операторите) в тялото на цикъла и след това се проверява стойността на израза, като при стойност различна от **0** (true) операторът се изпълнява отново. 
Ако изразът има стойност **0** (false), цикълът се преустановява. Следователно, първото изпълнение на оператора не зависи от това, изпълнено ли е условието или не и се изпълнява поне един път.
