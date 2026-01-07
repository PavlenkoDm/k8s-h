## Задание 1:

![Describe 1 pod data exchange (emptyDir)](./img/k8s-hw-volumes-1_1.jpg)

![Describe 2 pod data exchange (emptyDir)](./img/k8s-hw-volumes-1_2.jpg)

![Testing multitool volume](./img/k8s-hw-volumes-1_3.jpg)

---

## Задание 2:

![PV & PVC creation](./img/k8s-hw-volumes-2_1.jpg)

![Describe 1 pod data exchange (PVC)](./img/k8s-hw-volumes-2_2.jpg)

![Describe 2 pod data exchange (PVC)](./img/k8s-hw-volumes-2_3.jpg)

![Testing multitool output-data](./img/k8s-hw-volumes-2_4.jpg)

![Describe result output-data.txt](./img/k8s-hw-volumes-2_5.jpg)

- При Reclaim Policy Retain не происходит удаление pv при удалении pvc

![PVC deletion](./img/k8s-hw-volumes-2_6.jpg)

- Так же при Reclaim Policy Retain не происходит удаление файла при удалении pvc

![PVC deletion 2](./img/k8s-hw-volumes-2_7.jpg)

- Так же при удалении pv не происходит удаление файла потому что удаляется абстракция, а не сам файл.

![PV deletion](./img/k8s-hw-volumes-2_8.jpg)

---

## Задание 3:

![Enable microk8s provisioner](./img/k8s-hw-volumes-3_1.jpg)

![Apply sc-auto](./img/k8s-hw-volumes-3_2.jpg)

![Result of the classStorage pv file](./img/k8s-hw-volumes-3_3.jpg)

![Deletion of the sc-auto pvc](./img/k8s-hw-volumes-3_4.jpg)

---

- [Ссылка на containers-data-exchange.yaml manifest](./k8s/containers-data-exchange.yaml)
- [Ссылка на pv-pvc.yaml manifest](./k8s/pv-pvc.yaml)
- [Ссылка на sc-auto.yaml manifest](./k8s/sc-auto.yaml)
