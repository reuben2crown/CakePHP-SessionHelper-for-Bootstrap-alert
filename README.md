# CakePHP-SessionHelper-for-Bootstrap-alert
using bootstrap alert (danger, success, info, warning) with cake php $this->Session->setFlash()


#Requires Bootstrap
http://getbootstrap.com/


#How To
Just use this in your controller instead of the default
$this->Session->setFlash(__('Your account has been successfully activated'), 'default', array('class' => 'alert-success'));
