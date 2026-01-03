AWS Management Console

[Console Home | Console Home | ap-southeast-2](https://ap-southeast-2.console.aws.amazon.com/console/home?nc2=h_uta_mc&region=ap-southeast-2#)

original README -> [original README](./original-README.md)

---

check previous terraform apply output:

```bash
cd terraform
terraform show
terraform state list | grep crawler
cd -
```

check region:

```bash
aws configure get region
```

check crawlers:

```bash
aws glue get-crawlers --region ap-southeast-2
```

