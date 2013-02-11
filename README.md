Kohana234-sublimeText2-plugin
=============================

Kohana v 2.3.4, Keyboard shortcuts for sublime text 2

## Usage

Enter shortcut and press enter or tabulate.

**shortcut** : 

		description

### kohana
**kconf** : 

		Kohana::config('')

**klang** : 

		Kohana::lang('')

### ORM
**korm** : 

		ORM::factory('')

**kmodel** : 

		defined('SYSPATH') OR die('No direct access allowed.');
		
		class _Model extends ORM {
			
		}

### sessions
**ktsg** : 

		$this->session->get('')

**ktss** : 

		$this->session->set('', )

**kflash** : 

		$this->session->set_flash()

### url shortcuts
**kbase** : 

		url::base()

**kcurrent** : 

		url::current()

**kredirect** : 
		
		url::redirect()

###Others
**krender** : 
		
		$this->auto_render = false

**ktc** : 
		
		$this->template->content

### mail
**kswift** : 

		$swift = email::connect();
		$from = '';
		
		$subject = '';
		$message = '';
		
		$recipients = new Swift_RecipientList;
		$recipients->addTo('');
		$message = new Swift_Message($subject, $message, "text/html");
		$swift->send($message, $recipients, $from);
		$swift->disconnect();
		
### Database
**kquery** :

		$db = new database('');
		$query = "";
		$results = $db->query($query);

