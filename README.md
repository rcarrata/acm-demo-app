## Repository for demo Submariner and RHACM

All of this commands needs to be performed in the ACM Hub cluster to deploy through GitOps.

* Deploy the GuestBook App in cluster Managed 1

```
oc apply -k guestbook-app/acm-resources
```

* Deploy the Redis primary App in Cluster Managed 1

```
oc apply -k redis-primary-app/acm-resources
```

* Deploy the Redis secondary App in Cluster Managed 2

```
oc apply -k redis-secondary-app/acm-resources
```
