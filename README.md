# Python Documentation 

## Python version 3.7.5

### Lecture from Save In Your Brain

Numpy is A Python Library for dealing with numerical useful python package.

Use the Package manager [numpy](https://pip.pypa.io/en/stable/) to install numpy package.[Google](google.com)Press Facebook
[Facebook](www.facebook.com)
[Python](https://www.python.org/)

```bash
pip install numpy
```

##usage

```python
import numpy
numpy.pluralized('image') #returns 'Image'
numpy.pluralized('goose') #returns 'geese'
numpy.pluralized('phenomena') #returns 'phenmenon'
```

```java
package _model;

import java.io.Serializable;

import javax.persistence.Entity;
import javax.persistence.GeneratedValue;
import javax.persistence.GenerationType;
import javax.persistence.Id;
import javax.persistence.Table;

@Entity
@Table(name="Crust")
public class CrustBean implements Serializable{
	private static final long serialVersionUID = 1L;
	private Integer crustId;
	private Integer crustTypeId;
	private String crustTypeName;
	private Integer materialsId;
	private double quantity;
	private Integer unitPrice;

	public CrustBean() {}

	public CrustBean(Integer crustTypeId, String crustTypeName, Integer materialsId, double quantity,
			Integer unitPrice) {
		this.crustTypeId = crustTypeId;
		this.crustTypeName = crustTypeName;
		this.materialsId = materialsId;
		this.quantity = quantity;
		this.unitPrice = unitPrice;
	}

	@Id
	@GeneratedValue(strategy=GenerationType.IDENTITY)
	public Integer getCrustId() {
		return crustId;
	}

	public void setCrustId(Integer crustId) {
		this.crustId = crustId;
	}

	public Integer getCrustTypeId() {
		return crustTypeId;
	}

	public void setCrustTypeId(Integer crustTypeId) {
		this.crustTypeId = crustTypeId;
	}

	public String getCrustTypeName() {
		return crustTypeName;
	}

	public void setCrustTypeName(String crustTypeName) {
		this.crustTypeName = crustTypeName;
	}

	public Integer getMaterialsId() {
		return materialsId;
	}

	public void setMaterialsId(Integer materialsId) {
		this.materialsId = materialsId;
	}

	public double getQuantity() {
		return quantity;
	}

	public void setQuantity(double quantity) {
		this.quantity = quantity;
	}

	public Integer getUnitPrice() {
		return unitPrice;
	}

	public void setUnitPrice(Integer unitPrice) {
		this.unitPrice = unitPrice;
	}

}
```
```c#
(display-battery-mode 1)
(display-time-mode 1)

;; A dirty hack to display the current workspace on the
;; mode-line.  I prefer it to adding a new item to
;; global-mode-string due to a different placement on the
;; mode-line.  Semantically the meaning is close enough to
;; the original meaning of this variable, so I'll leave it
;; this way.
(setq mode-line-frame-identification
      '(:eval (propertize
               (format "X%s "
                       (funcall exwm-workspace-index-map
                                exwm-workspace-current-index))
               'face 'bold)))

(require 'exwm-randr)
(exwm-randr-enable)

(defun jethro/launch (command)
  (interactive (list (read-shell-command "$ ")))
  (start-process-shell-command command nil command))

(defun jethro/exwm-terminal ()
  (interactive)
  (call-process "urxvtc"))

(exwm-input-set-key (kbd "s-SPC") #'jethro/launch)
(exwm-input-set-key (kbd "C-c C-p") #'ivy-pass)
(exwm-input-set-key (kbd "C-x t") #'jethro/exwm-terminal)

(add-hook 'exwm-manage-finish-hook
          (lambda ()
            (when (and exwm-class-name
                       (string= exwm-class-name "URxvt"))
              (exwm-input-set-local-simulation-keys '(([?\C-c ?\C-c] . ?\C-c))))))

(exwm-enable)

(provide 'exwm-config)
```

![alt](https://www.stellaandchewys.com/wp-content/uploads/maplechristmas.jpg)
![alt](https://static01.nyt.com/images/2014/01/28/science/28SLOT_SPAN/28SLOT-jumbo.jpg)
![alt_death note](https://www.thecinemaholic.com/wp-content/uploads/2018/07/Death-Note-release-date-1024x500.jpg)
![alt_lunox](https://pm1.narvii.com/7433/c9d9e67cb050302f89214478c1584857cfa3368fr1-1242-771v2_hq.jpg)

<img src="https://www.thecinemaholic.com/wp-content/uploads/2018/07/Death-Note-release-date-1024x500.jpg" alt="death note" width="193" height="130">

                                                                                                                                                

##Contributing

```
Pull Request are Welcome.For Major Changes,Please open an issue first to discuss what you would like to change.
```

```
Make Software.For Major Changes, Please open the new world.
```

```python
from math import pi
```
-numpy

-matplotlib

-scipy

-tensor-core

Please make sure to update tests as appropirate.

-!{#FF000}'RED'

```diff
-text in red
+text in green
!text in orange
#text in grey
```
```diff
-Red
+Green
!Orange
#Grey

```diff
-text 
+word
!character
#string
```
[Htoo Hunn](https://www.facebook.com/profile.php?id=100012260919102)
[MIT](https://choosealicense.com/licenses/mit/)
