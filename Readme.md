If you have any problems executing the commands executed in the section, you can refer back to this list.

The complete command list is also present on the github repository.

https://github.com/in28minutes/devops-master-class/tree/master/kubernetes#commands

Commands

1.  docker run -p 8080:8080 in28min/hello-world-rest-api:0.0.1.RELEASE

2.

3.  kubectl create deployment hello-world-rest-api --image=in28min/hello-world-rest-api:0.0.1.RELEASE

4.  kubectl expose deployment hello-world-rest-api --type=LoadBalancer --port=8080

5.  kubectl scale deployment hello-world-rest-api --replicas=3

6.  kubectl delete pod hello-world-rest-api-58ff5dd898-62l9d

7.  kubectl autoscale deployment hello-world-rest-api --max=10 --cpu-percent=70

8.  kubectl edit deployment hello-world-rest-api #minReadySeconds: 15

9.  kubectl set image deployment hello-world-rest-api hello-world-rest-api=in28min/hello-world-rest-api:0.0.2.RELEASE

10.

11. gcloud container clusters get-credentials in28minutes-cluster --zone us-central1-a --project solid-course-258105

12. kubectl create deployment hello-world-rest-api --image=in28min/hello-world-rest-api:0.0.1.RELEASE

13. kubectl expose deployment hello-world-rest-api --type=LoadBalancer --port=8080

14. kubectl set image deployment hello-world-rest-api hello-world-rest-api=DUMMY_IMAGE:TEST

15. kubectl get events --sort-by=.metadata.creationTimestamp

16. kubectl set image deployment hello-world-rest-api hello-world-rest-api=in28min/hello-world-rest-api:0.0.2.RELEASE

17. kubectl get events --sort-by=.metadata.creationTimestamp

18. kubectl get componentstatuses

19. kubectl get pods --all-namespaces

20.

21. kubectl get events

22. kubectl get pods

23. kubectl get replicaset

24. kubectl get deployment

25. kubectl get service

26.

27. kubectl get pods -o wide

28.

29. kubectl explain pods

30. kubectl get pods -o wide

31.

32. kubectl describe pod hello-world-rest-api-58ff5dd898-9trh2

33.

34. kubectl get replicasets

35. kubectl get replicaset

36.

37. kubectl scale deployment hello-world-rest-api --replicas=3

38. kubectl get pods

39. kubectl get replicaset

40. kubectl get events

41. kubectl get events --sort.by=.metadata.creationTimestamp

42.

43. kubectl get rs

44. kubectl get rs -o wide

45. kubectl set image deployment hello-world-rest-api hello-world-rest-api=DUMMY_IMAGE:TEST

46. kubectl get rs -o wide

47. kubectl get pods

48. kubectl describe pod hello-world-rest-api-85995ddd5c-msjsm

49. kubectl get events --sort-by=.metadata.creationTimestamp

50.

51. kubectl set image deployment hello-world-rest-api hello-world-rest-api=in28min/hello-world-rest-api:0.0.2.RELEASE

52. kubectl get events --sort-by=.metadata.creationTimestamp

53. kubectl get pods -o wide

54. kubectl delete pod hello-world-rest-api-67c79fd44f-n6c7l

55. kubectl get pods -o wide

56. kubectl delete pod hello-world-rest-api-67c79fd44f-8bhdt

57.

58. kubectl get componentstatuses

59. kubectl get pods --all-namespaces

60.

61. gcloud auth login

62. kubectl version

63. gcloud container clusters get-credentials in28minutes-cluster --zone us-central1-a --project solid-course-258105

64.

65. kubectl rollout history deployment hello-world-rest-api

66. kubectl set image deployment hello-world-rest-api hello-world-rest-api=in28min/hello-world-rest-api:0.0.3.RELEASE --record=true

67. kubectl rollout undo deployment hello-world-rest-api --to-revision=1

68.

69. kubectl logs hello-world-rest-api-58ff5dd898-6ctr2

70. kubectl logs -f hello-world-rest-api-58ff5dd898-6ctr2

71.

72. kubectl get deployment hello-world-rest-api -o yaml

73.

...

[Message clipped]  View entire message
